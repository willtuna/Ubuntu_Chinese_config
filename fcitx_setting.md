# Ubuntu: fcitx + chewing 新酷音輸入法

fcitx 輸入法架構比預設的 ibus 穩定許多。

1. 安裝 `fcitx` (框架) 以及 `fcitx-chewing` (框架下的新酷音輸入法)：

        sudo apt-get install fcitx fcitx-chewing

2. 設為預設輸入法架構： **System Settings** > **Language Support** > **Language** Tab > **Keyboard input method system:** set to **fcitx**
3. 讓每個程式獨立維持輸入法狀態： **System Settings** > **Keyboard** > **Typing** Tab > Click on **Text Entry** > Select **Allow different sources for each application**
4. fcitx 設定沒事別跳出選字框： 右上角工具列 fcitx 鍵盤圖示 > **Configure** > **Global Config** > Click **Show Advance Option** > **Appearance** > **Do not show input window if there is only preedit string**
5. 下載這個 Gist 的圖示，取代原本新酷音超不搭的圖示，符合 Ubuntu Ambiance 主題風格:

        sudo cp fcitx-chewing.png /usr/share/icons/hicolor/48x48/apps/fcitx-chewing.png
