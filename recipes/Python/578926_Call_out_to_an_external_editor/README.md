## Call out to an external editorOriginally published: 2014-09-01 16:02:42 
Last updated: 2014-09-01 18:26:51 
Author: Steven D'Aprano 
 
Here's a function that lets you use Python to wrap calls to an external editor. The editor can be an command line editor, like venerable old "ed", or something more powerful like nano, vim or emacs, and even GUI editors. After the editor quits, the text you typed in the editor is returned by the function.