# 書籍「ChatGPT APIとPythonで音声対話型チャットボットを作ろう」のサポートページ

こちらは、書籍「ChatGPT APIとPythonで音声対話型チャットボットを作ろう」のサポートページです。

## 書籍の紹介

人工知能（AI）の進化とその可能性を、実際に手を動かして学びたい方へ。「ChatGPT APIとPythonで音声対話型チャットボットを作ろう」は、AI技術を活用したチャットボットの作成を初心者にも分かりやすく解説した一冊です。

本書では、まず開発環境の構築からスタートします。ChatGPTの概要から、実際にチャットボットを作成するまでの手順を丁寧に解説します。また、OpenAIの音声認識APIの利用方法やVOICEVOXを利用した音声合成の方法も詳しく紹介。最後は、猫のキャラクターと音声で会話できる、音声対話型チャットボットを作成します。

本書に記載されたソースコードは、GitHubで公開しています。具体的なプログラム作成を通じて、AIとの対話を実現するテクニカルな知識を得ることができます。

これからのAI時代に向けて、一緒に学んでみませんか？

## 目次

### はじめに

- ChatGPTとは
    - ChatGPTの概要
    - ChatGPTとAPI
- 本書の目的
- サンプルコード
- 免責事項
- 商標

### 第1章 開発環境の構築

- 1.1.Homebrewのインストール
- 1.2.Pythonのインストール
- 1.3.VSCodeのインストール
    - 1.3.1.日本語環境の設定
    - 1.3.2.Python拡張機能のインストール
    - 1.3.3.ターミナルからVSCodeを起動できるようにする
- 1.4.開発用のディレクトリを作成する
- 1.5.サンプルコードのダウンロード
- 1.6.venvの設定
- コラム1：最低限覚えておきたいUNIXコマンド

### 第2章 テキスト型チャットボットの作成

- 2.1.ChatGPTとプロンプト
- 2.2.テキストチャットボットのプログラム
- 2.3.プログラムの解説
- コラム2：LangChainを使ってみよう

### 第3章 音声認識の実装

- 3.1.サンプルコード1:単純な音声認識
    - 3.1.1.サンプルコード1の解説
- 3.2.サンプルコード2:録音の開始と終了を制御する
    - 3.2.1.サンプルコード2の解説

### 第4章 音声合成の実装

- 4.1.VOICEVOXのインストール
    - 4.1.1.VOICEVOXの動作確認
    - 4.1.2.VOICEVOXのAPIドキュメント
- 4.2.音声合成のプログラム
- 4.3.プログラムの解説

### 第5章 音声対話型チャットボットの作成

- 5.1.処理を関数化して外部から呼び出せるようにする
- 5.2.チャットボット本体の作成
- 5.3.音声対話型チャットボットの実行
- 5.4.応用に向けて

## サンプルコードの実行方法

### ライブラリのインストール

```zsh
pip install -r requirements.txt
```

### Chapter02

テキスト対話型チャットボットの実行方法です。事前にOpenAIのAPIキーを取得し、`your-api-key`を置き換えてください。

```zsh
cd Chapter02
python text_chat_bot.py
```

### Chapter03

音声認識サンプルコード1の実行方法です。事前にOpenAIのAPIキーを取得し、`your-api-key`を置き換えてください。

```zsh
cd Chapter03
python speech_to_text_01.py
```

音声認識サンプルコード2の実行方法です。事前にOpenAIのAPIキーを取得し、`your-api-key`を置き換えてください。

```zsh
cd Chapter03
python speech_to_text_02.py
```

### Chapter04

音声合成サンプルコードの実行方法です。事前にVOICEVOXをインストールし、起動してください。

```zsh
cd Chapter04
python text_to_speech.py
```

### Chapter05

音声対話型チャットボットの実行方法です。事前にOpenAIのAPIキーを取得し、`your-api-key`を置き換えてください。

```zsh
cd Chapter05
python voice_chat_bot.py
```

## 追補資料

### Windows環境における環境構築方法

[こちら](Windows.md)を参照してください。
