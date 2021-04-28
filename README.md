# chia-ploter
easy way to plot

Start a process, specify the temporary directory and the destination directory, and use the temporary directory plots continuously to the destination directory

Read this in other languages: English | [简体中文](https://github.com/binjie09/chia-ploter/blob/main/README-zh_CN.md)
## START
```
npm install chiaP -g
chiaP -t D:\temp\a -d E:\chia
```
![](https://github.com/binjie09/chia-ploter/blob/main/img/20210427002246.jpg)
## TODO List

- [x] Infinite loop chia plots
- [x] filter some logs and show progress
- [ ] If the temporary directory is full, automatically terminate the Plot task process with the lowest progress
- [ ] support linux chia automatic detection
