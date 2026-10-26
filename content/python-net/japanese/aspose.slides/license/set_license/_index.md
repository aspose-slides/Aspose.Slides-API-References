---
title: set_license method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
コンポーネントにライセンスを設定します。

```python
def set_license(self, license_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| license_name | **str** | 完全なファイル名または短いファイル名、もしくは埋め込みリソースの名前を指定できます。<br/><br/>空文字列を使用すると評価モードに切り替わります。 |

### 備考

次の場所でライセンスを検索します：

1. 明示的なパス。
2. コンポーネント アセンブリのフォルダー。
3. クライアントの呼び出しアセンブリのフォルダー。
4. エントリ アセンブリのフォルダー。
5. クライアントの呼び出しアセンブリに埋め込まれたリソース。

**注意:** .NET Compact Framework では、ライセンスは次の場所でのみ検索されます：

1. 明示的なパス。
2. クライアントの呼び出しアセンブリに埋め込まれたリソース。

## set_license(self, stream) {#iorawiobase}
コンポーネントにライセンスを設定します。

```python
def set_license(self, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | ライセンスが含まれるストリーム。 |

### 備考

このメソッドを使用して、ストリームからライセンスをロードします。

### 参照
* クラス [`License`](/slides/python-net/ja/aspose.slides/license)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)