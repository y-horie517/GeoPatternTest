# GeoPatternTest
gem：GeoPattern使用テスト用アプリ

GeoPatternとは
GeoPatternとは、文字列を与えてSVG画像を生成するライブラリです。 与えた文字列はハッシュに変換され、それをもとに幾何学パターン（全16種）や色相、彩度が決定されます。事前に指定することも可能です。 本家RubyGem版の他に、有志による各言語での実装が揃っています（後述）。

生成した画像はCSSのbackground-imageでの利用が想定されています。タイル型の画像を出力するので、それを縦方向・横方向にリピートして表示します。base64 に変換することもできるので便利ですよ
