Kuin.tmLanguage
===============

Kuin syntax definitions for Sublime Text 2

#### インストール

1. SublimeText2の"Packages"ディレクトリを開きます (Preferences > Browse Packages...)
2. "Kuin" ディレクトリ開きます (無ければ作ってください)
3. このリポジトリをクローンするか、Kuin.tmLanguageファイルをコピーします

#### つかいかた

デフォルトでknの拡張子を持つファイルは自動でこの定義ファイルによってハイライトされます。

割り当てる拡張子を変更する必要があれば、Kuin.tmLanguageファイルをエディタで開き、dict > key[fileTypes] > array/string を編集してください。


数値リテラルや、いくつかの@in/@nin等の演算子については未対応です。
コメントのネストも未対応です。

{ Kuin 0.3で文法が固定されるみたい[要出典]なので、その後にちゃんとした定義ファイルに更新します。 }
