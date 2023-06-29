## <p align="center">mov rsi, 0x8000000000000000</p>


``` C
                          struct movrsi { char *name; char *interests[5]; char *languages[5]; };
```
##

```C
                              static const struct movrsi about_me = {
                                  .name  = "movrsi",
                                  .interests = {
                                     "Application development",
                                     "Code optimization",
                                     "Cracking",
                                     "Debugging",
                                     "Reverse Engineering"
                                  },
                                  .languages = {
                                `     "C",
                                      "C++",
                                      "Javascript",
                                      "Python",
                                      "QT"       
                                  }
                              };
```
