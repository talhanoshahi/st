st - simple terminal
====================
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

Patches Applied
---------------
1. [externalpipe - 0.8.4](https://st.suckless.org/patches/externalpipe/)
2. [scrollback - 20210507-4536f46](https://st.suckless.org/patches/scrollback/)
3. [externalpipe eternal - 0.8.3](https://st.suckless.org/patches/externalpipe/)
4. [delkey - 20201112 - 4ef0cbd](https://st.suckless.org/patches/delkey/)
5. [st-font2 - 0.8.5](https://st.suckless.org/patches/font2/)
6. [workingdir - 20200317 - 51e19ea](https://st.suckless.org/patches/workingdir/)
7. [alpha - 20220206 - 0.8.5](https://st.suckless.org/patches/alpha/)
