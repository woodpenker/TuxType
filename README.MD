由于此项目在GitHub上开发者没有放代码，这里我就放了一个源代码拷贝，版本1.8.1。此项目来自<a href='http://tux4kids.alioth.debian.org/tuxtype/'>http://tux4kids.alioth.debian.org/tuxtype/</a>。（似乎好久都没更新了，以后有时间我就把作者的TODO试着做一做）
___
以下英文说明是原来的说明，目前修改了游戏部分，增加了几个快捷键：
###在fish cascade中：
F3可以增加剩余鱼的数量；
F4可以减少剩余鱼的数量。
原来的F6 F7分别是剩余生命加减10。
###在ZAP中增加了：
F1进入下一等级
F2进入上一等级
F3重置所有建筑为初始状态（作弊用）
___
安装需要安装libsdl1.2的多个库,Ubuntu下建议使用sudo apt install libsdl-*-dev
___

NOTE - this document is reasonably correct but not completely current.
It will updated as the maintainer's time allows - DSB


Tux Typing:
An Educational Typing Tutor Game Starring Tux, the Linux Penguin
----------------------------------------------------------------

(To install the game on your system, please read the INSTALL file.)

    If you are interested in Translation/moving this game to another 
    language, please send a mail to 

    David Bruce <davidstuartbruce@gmail.com>, 
    Holger Levsen <debian@layer-acht.org>,  or to:

    <tux4kids-tuxtype-dev@lists.alioth.debian.org>

    Additional information on this subject is covered in "HowToTheme.html"
    in the "doc/en" directory of this package.

(Updated 04 Apr 2010)

This is version 1.8.1 of Tux Typing.

In Fish Cascade you control Tux as he searches for fish to eat. Fish fall
from the top of the screen. These fish have letters on them.  Unforunately
for Tux, eating a fish with a letter on it will cause his stomach to
become ill, so it is up to you to help Tux eat fish!  By typing the
letters, it will cause them to disappear so tux can chow down on the 
fish.

In Comet Zap you control Tux as he defends the cities from comets.  To
protect a city from a comet, type the letter on the comet and it will
cause Tux to destroy it with a laser! (In case you wondered, Comet Zap
is an adaptation of the *great* math drill game, "Tux, of Math Command").

"Lessons" and "Phrase Typing" are additional typing activities.

"Phrase Typing" involves typing of phrases or complete sentences, with 
measurment of accuracy and typing speed. The current phrases in the default
(English) theme are a collection of pangrams (sentences with all 26 letters)
as well as some well-known quotes from public domain literature. At some point
we will make this easy for teachers to modify, so sentences related to a
current study topic might be used.

"Lessons" uses XML-based scripting to run various other parts of the program in
a specified order, including the "Practice" activity.  As of version 1.8.0, the
default theme for Tux Typing now has a substantial collection of finger exercises
("basic_lesson_01" to "basic_lesson_43") that progressively introduce the keys
on the keyboard. We intend to further develop this in upcoming months with
display of descriptive lesson titles, tracking of student progress, and so forth.

These features are not yet completed, but represent ways to add additional
"content" without requiring more programming per se.


Word List Editor:

Tux Typing 1.8.0 now has the ability to add and modify custom word lists from within
Tux Typing itself (it has always been possible to do this by editing the word list
files directly - they are plain text files). The editor feature is at a beta stage - it basically works, but has room for improvement.

Note that the word lists included with Tux Typing are not modifiable with this feature, due to file system permissions (Tux Typing is run as an ordinary user, but the bundled word lists and other data files normally can only be modified by a user with root or sudo status).

Tux4Kids is developing a complete, GUI-based administration/configuration program for Tux Typing, Tux Math, and Tux Paint. Tux4Kids-Admin will be much more powerful and
flexible than the in-game word list editor. However, it is not completed.

Tux Typing is Free Software, distributable under the GNU General Public
License. Please read COPYING for more info.

Enjoy!

David Bruce
davidstuartbruce@gmail.com

(previous maintainer -Jesse Andrews -- jdandr2@uky.edu
 http://tux4kids.net/~jdandr2)
