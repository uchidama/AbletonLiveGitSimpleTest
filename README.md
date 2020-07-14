# AbletonLiveGitSimpleTest
<a href="https://gyazo.com/b873ba3891a95938341e6bb46a96b649"><img src="https://i.gyazo.com/b873ba3891a95938341e6bb46a96b649.png" alt="Image from Gyazo" width="640"/></a>  
Ableton Live Git Simple Test

# 技術メモ
.gitignoreやら.gitattributeやら設定すれば、gitでAbleton Liveのプロジェクトをまるっと管理出来るのではないか？  
と思ったけどレコーディングしてる音声ファイルがあるとファイルの参照がコケてダメみたい。  

元々Ableton Liveに入ってるパッキング機能を使ってalpファイルを作って、それをgit-lfsで管理するのが良さそうだ。

## Ableton Live ALPの作り方
### 英語版
<a href="https://gyazo.com/c8f75e08b3a833ae63d209d2986d0f2f"><img src="https://i.gyazo.com/c8f75e08b3a833ae63d209d2986d0f2f.png" alt="Image from Gyazo" width="235"/></a>  
File -> Manage Files -> Manage Project -> Packing "Create Pack"  

### 日本語版
<a href="https://gyazo.com/f7cb85434bc574e9ecf014a7606ecc3f"><img src="https://i.gyazo.com/f7cb85434bc574e9ecf014a7606ecc3f.png" alt="Image from Gyazo" width="235"/></a>

# おまけ
[このプロジェクトで再生されるサウンド](https://youtu.be/V-zpshjV-eo)  
MIDIだけの入力だと管理するファイルが単純過ぎて確認にならないので、ギターも録音して入れた。
