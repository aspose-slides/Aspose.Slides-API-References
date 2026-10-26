---
title: set_license method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
コンポーネントにライセンスを設定します。

```python
def set_license(self, license_name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| license_name | **str** | 完全なファイル名または短いファイル名、または埋め込みリソースの名前を指定できます。<br/><br/>空の文字列を使用して評価モードに切り替えます。 |

### 備考

次の場所でライセンスを検索します：

1. 明示的なパス。

2. コンポーネント アセンブリのフォルダー。

3. クライアントの呼び出しアセンブリのフォルダー。

4. エントリ アセンブリのフォルダー。

5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**注:** .NET Compact Framework の場合、次の場所でのみライセンスを検索します：

1. 明示的なパス。

2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

## set_license(self, stream) {#iorawiobase}
コンポーネントにライセンスを設定します。

```python
def set_license(self, stream):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | ライセンスを含むストリーム。 |

### 備考

このメソッドは、ストリームからライセンスを読み込むために使用します。

### 参照
* クラス [`ILicense`](/slides/python-net/ja/aspose.slides/ilicense)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)