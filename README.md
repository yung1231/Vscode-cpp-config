# Vscode-c-config
# MinGW
下載 [MinGW](https://sourceforge.net/projects/mingw/)

![](https://i.imgur.com/gmTK92e.png)

安裝

![](https://i.imgur.com/a3erufg.png)

![](https://i.imgur.com/5fP2e9t.png)

找到 `mingw32-gcc-g++` 後勾選，按下 `Apply Changes`

![](https://i.imgur.com/4IEpp4q.png)

將 `D:\MinGW\bin` 加入到環境變數中

檢查 MinGW 是否安裝成功
```
gcc --version
g++ --version
gdb --version
```

# vscode
安裝插件

![](https://i.imgur.com/Ol7YCM0.png)

# vscode
![](https://i.imgur.com/MbRXOpp.png)

創建一個資料夾，把四個檔案下載下來，創建一個 `.vscode` 資料夾裡面
> [config](https://github.com/yung1231/Vscode-cpp-config.git)

之後寫的 code 要放在該資料夾下面

`Ctrl+Shift+B` 可以進行編譯

> `.vscode` 必須要與被編譯的檔案放在同一個資料夾或是任一上層目錄

## 測試
```cpp
#include<iostream>
using namespace std;

int main(){
  cout<<"Hello World\n";

  return 0;
}
```

# Debug
![](https://i.imgur.com/aemHyq9.png)

要使用時，路徑不能有中文名稱