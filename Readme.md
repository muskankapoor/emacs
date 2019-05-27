

**Emacs Commands**
1. Org Mode
  * #+STARTUP: showall 
  * above (startup) control expands all 
  2. LInks
   * ctrl c ctrl l to add link
  3. example
 #+BEGIN_SRC emacs-lisp
 (+ 2 3)
 #+END_SRC
 ctrl x ctrl e to (elisp inside org mode)
 or ctrl c ctrl c in the code block itself to get results

2. try allows to try packages 
 * ctrl-h P describe-package 
  
3. commands
 * ctrl x + (bigger)
 * ctrl x - (smaller)
 * save alt x (escape x)
 * ctr x ctrl f create file (.org to create .org)
 * ctrl x ctrl e to execute
 * ctrl p, n, f (to move arrow previous, next front) 
 * ctrl s for search 
 * ctrl r for search backwards
 * alt f to move forward
 * alt b to move backwards
 * with swiper mode things get better, incremental search 
 counsel-ctrl x ctrl f 

4. automcompete
 * alt / automcptletes
 
5. switch buffers
 * C-x C-b	list-buffers
 * C-x b	switch-buffer
 * C-X C-x to list
 * M-x kill-some-buffers


6. windows 
 * C-c left or right to move through past window configurations.
 * C-x 2	split-window-below (vertically)
 * C-x 3	split-window-right (horizontally)
 * C-x 0	delete-window (this one)
 * C-x 1	delete-other-windows
 * C-x o	other-window (moves foxus to the next window) goes to other window 
 * C-C- (LEFT KEY) undo confirugration
 * c-c (right key)redo 
 * terminal
   g++ ...
   a.exe 
 * MinGW32-make 
 
7. For mac: open in terminal 
 * open -a Emacs a.txt
 * terminal check dependencies
 g++ -MM main.cpp   
 g++ -MM *cpp (tells for all)


8. c++:
 * io tab
 * int tab
 * alt x-compile
 * alt x shell 
 * specific to mac and windows above





