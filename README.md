# **42 Header**

42 (Paris)

### **Modified by paikwiki**

환경변수 `$USER`와 `$MAIL` 대신 각각 `$USER_42`와 `$MAIL_42`를 사용하도록 변경했습니다. 

사용법은 기존 42header와 동일하며, 환경변수 끝에 각각 `_42`만 붙여서 적용하면 됩니다.

### **Description**

42 standard header for vim editor.

![42 header](img/42header.jpg)

### **UNIX Setup**

Add in `~/.zshrc` your:

+ `USER`
+ `MAIL`

Copy `stdheader.vim` in your `~/.vim/plugin`.

### **Usage**

In **NORMAL** mode you can use `:Stdheader` or simply press the shortcut <kbd>F1</kbd>.

Under **Linux** you eventually need to disable the **help** shortcut of your **terminal** :

For **Terminator**, right click -> Preferences -> Shortcuts -> change help with something other than <kbd>F1</kbd>

### **Note**

Inside the **42 clusters** you can easily run:

`$ ./set_header.sh`

### **Credits**

[@zazard](https://github.com/zazard)

### **License**

This work is published under the terms of **[42 Unlicense](https://github.com/gcamerli/42unlicense)**.
