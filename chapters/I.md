# Appendix I: Creating a New Example Project

## Prerequisite
* Completed one of the following Appendix A-H.

## Create A New Project

### OS X and Linux users.

		$ cd Cocos2d-x
		$ ./setup.py
		$ source ~/.bash_profile
		$ cocos new MyGame -p com.MyCompany.MyGame -l cpp -d ~/MyCompany

![](I-img/1.png "")

* `MyGame`: name of your project
* `-p com.MyCompany.MyGame`: package name for android
* `-l cpp`: programming language used for the project, valid value is `cpp`and `lua`
* `-d ~/MyCompany`: directory to hold your project

		$ cocos run -s ~/MyCompany/MyGame -p ios

* `-s`: directory of the new project. This could be an absolute path or a relative path.
* `-p`: which platform to run on. Options are `ios`,`android`,`win32`,`mac` and `linux`.

![](I-img/2.png "")

(Note: You are a tmux user, you should add `reattach-to-user-namespace` before the
command `cocos`. For more information, please refer to
[https://github.com/phonegap/ios-sim](https://github.com/phonegap/ios-sim) for
more information.)

You can run `cocos run --help` for more detail information.

### Win32 Users
using `cmd` as your shell: `cd Cocos2d-x-3.1.1\tools\cocos2d-console\bin` or to
wherever you have this on your filesystem

		`cocos.py new YourGameTitle -p com.yourcompany.gametitle -l cpp -d C:\YourGameTitle`
