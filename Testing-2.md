# GNU nano 9.1 CLI Text Editor Released with Minor Improvements and Bug Fixes
GNU nano 9.1 (codename “met een hongerig paard aan ons been“) has been released today as the latest stable version of this popular, free, and open-source command line editor for Linux.

Coming two and half months after [GNU nano9.0](https://9to5linux.com/gnu-nano-9-0-cli-text-editor-released-with-new-features-and-improvements), the GNU nano 9.1 release is a small update that only makes the M-Ins and M-Del key bindings rebindable, shifts the viewport to the left where possible when searching, removes the ability to read and write files in old Mac format, and deprecates the ^T toggle between WhereIs and GotoLine.

On top of that, GNU nano 9.1 addresses a couple of issues, one of which caused backups to fail or had the wrong timestamp when the --backup option was active, and another causing .save files to not be chmodded to the permissions of the base file, nor chowned to its owner, when nano is killed or crashes.

GNU nano 9.1 is the first point release to the GNU nano 9.0 series, which introduced support for scrolling the viewport sideways in steps of one tabsize, support for scrolling all lines sideways together when the cursor almost goes offscreen, and the ability to rebind the M-Left, M-Right, M-Up, and M-Down key bindings.

GNU nano 9.0 also introduced support for canceling a recording when stopping the recording of a macro immediately after starting it, leaving an existing macro in place, as well as the ability to click in the scrollbar area to roughly navigate within the buffer by using --mouse and --indicator.

For more details about the changes included in the latest GNU nano realeses, check out the [*realese notes*](https://www.nano-editor.org/news.php). Meanwhile, you can download GNU nano 9.1 rght now from the [*official website*](https://www.nano-editor.org/download.php) as a source tarball if you fancy compiling software from source.

If that’s not your cup of tea, you will have to wait for the new GNU nano release to land in the stable software repositories of your favorite GNU/Linux distribution to update and enjoy the improvements.If that’s not your cup of tea, you will have to wait for the new GNU nano release to land in the stable software repositories of your favorite GNU/Linux distribution to update and enjoy the improvements.

