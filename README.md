# InterfaceSample

## 概要
- インターフェース依存のプログラムを作成する。
- 複数のパッケージからなるプログラムを作成する。
- インターフェース、ファイル出力するクラスを1つずつ、インターフェースをインポートして使うクラスを2種類作る。
- 足し算のプログラムを出力してみて、その後引き算に書き換え、修正箇所をチェックして依存関係を確かめる。

## 修正箇所
「src.main.java.chapter03.use.call」の11行目
``Calculator calculator = new AddCalc();``
11行目の内容（足し算 ）を12行目の内容（引き算）に変換する。
`Calculator calculator = new SubCalc();`
出力結果はそれぞれ、11行目では15、12行目では5となる。
