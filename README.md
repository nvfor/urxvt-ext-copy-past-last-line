# urxvt-ext-copy-past-last-line
urxvt plugin that allow you to paste last printed line to the prompt and may be bound to keysym

place cppst file to ~/.urxvt/ext

add this to .Xresources

  URxvt.perl-ext: cppst
  URxvt.keysym.M-z: perl:cppst:activate


After that you will need to 

  xrdb -merge .Xresources


