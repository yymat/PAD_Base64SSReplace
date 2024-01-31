<div id="top"></div>

<!-- ## 使用技術 -->
<!-- シールド一覧 -->
<!-- https://t8csp.csb.app/ -->
<p style="display: inline">
  <img src="https://img.shields.io/badge/-Power%20Automate%20Desktop-5391FE.svg?logo=Power%20Automate&style=popout"
</p>
Power Automate Desktop UI picture change sub tool

# Power Automate DesktopのUI要素のキャプチャ画像を修正する


# 概要

Power Automate Desktop（以降はPADと表記）でUI要素は画像データも一緒に保存されてしまいアカウント情報など、外部に表示したくない場合に、画像データ部分を修正することができない。

セキュリティ対策の一環として画像データを修正する際に使用するフローです。

![base](https://github.com/yymat/PAD_Base64SSReplace/assets/61073941/9fd0c45b-380d-4b6e-93e0-d8f213d9b1ab)

# 前提

フローをコピペするさいにUI要素の画像データもコピーされるが
修正できないので当PADを補助的に使用して画像データを修正する

UI要素の画像データはBase64のようです。

# 導入方法

Base64ScreenShotReplace.zipを解凍して全文をコピーする。

新規のフローを作成し、コピーしたソースをフローに貼り付ける（Ctrl＋V）。

# 使い方

PADフローを参照（詳細は後日に…）

テキストから画像データ部分を変数に入れて、フローを実行し画像ファイルを作成する。

モザイク等処理をかけて画像を保存。

そのファイルを指定して読み込んでBase64に変更してPADのフローの画像データを置き換える


# ライセンス
 [MIT license](https://en.wikipedia.org/wiki/MIT_License).
