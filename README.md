# Blinky Flappers!

*Blinky Flappers!* is the unofficial DDLC expansion fan-mod that adds animation-like face expressions to the sprites and CGs.  
Made by yamamotoNEW. Thanks to the Renpy Tom and some Ren'py experts who made the sample scripts of blinking and mouth-flapping.  

『Blinky Flappers!』はDDLCの立ち絵/イベントCGに表情アニメーションを追加する非公式拡張ファンMODです。  
作者は山本ニューですが、Ren'pyの開発者Renpy Tom氏をはじめとする先達のまばたき・口パク実装スクリプトを大いに参考にしました。ありがとうございます。  

## How to play

Download here: https://github.com/yamamotoNEW/Blinky-Flappers-MOD/releases

Extract the zip,copy `game` folder, paste it on original DDLC's `game` folder and start the game.  
**DON'T USE THE Steam ver. DDLC. DOWNLOAD THE VANILLA DDLC AND USE IT, PLEASE.**  

すでに[日本語化パッチ](https://steamcommunity.com/sharedfiles/filedetails/?id=1296040205)適用済のDDLCをお持ちの方は、Blinky Flappers!を展開して出てくるgameフォルダをそれに上書きしてゲームをスタートすればOKです。  
お持ちでない方は、公式から新しくDDLCをダウンロード→非公式日本語パッチを適用→Blinky Flappers!を適用、の順番でパッチを当ててください。**（DDLCは必ず新たにダウンロードしてください！）**  

## Include in your own fan-mod

Copy `mod_assets` to the fan MOD you want to bundle, and refer to the following files according to the part you want to apply the animation to.

- `cgs.rpy` - Event CG
- `definitions.rpy` - Sprites
- `script-ch30` - Act3 CG
- `splash.rpy` - Title

----

`mod_assets` を同梱したいファンMODにコピーし、アニメーションを適用したい部分に応じて以下のファイルを参照してください。

- `cgs.rpy` - イベントCG
- `definitions.rpy` - 立ち絵
- `script-ch30` - Act3のCG
- `splash.rpy` - タイトル

## LICENCE

Feel free to use them in your own fan-mod or modify them. No need to inform me or credit me.  

あなたの作成したファンMODに同梱することが可能です。その際、許可を求めたりクレジットしたりする必要はありません。  

## Special thanks

- Renpy Tom and other Ren'py developers - The algorithm of blinking and mouth-flapping
- Satchely - I modified the expression assets she drew
- 宇佐城 Usagi [Twitter@usajou](https://twitter.com/usajou) : tester and other help
- はおたど Haotado [Twitter@hadowater](https://twitter.com/hadowater) : drew one of Sayori's expression
- Proudust [@proudust](https://github.com/proudust) : programming advices
