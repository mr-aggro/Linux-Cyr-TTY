# Linux-Cyr-TTY
How to make Cyr in Raspberry Pi for TTY

1) nano /etc/default/keyboard


  	modify: XKBLAYOUT="us,ru"
	
	
2) sudo dpkg-reconfigure keyboard-setup
  
	
  	choose en_US.UTF-8, ru_RU.UTF-8
	
	
3) sudo dpkg-reconfigure console-setup
  
	
  	choose Cyrillic - Slavic languages
  
  
4) nano /etc/profile


  	add in the end of file:
  
  
  	export LANG="en_US.UTF-8"
  	export LC_ALL="en_US.UTF-8"
