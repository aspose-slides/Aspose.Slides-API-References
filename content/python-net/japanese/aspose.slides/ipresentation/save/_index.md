---
title: save method
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
プレゼンテーションのすべてのスライドを、XAMLマークアップを表すファイルのセットに保存します。

```python
def save(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ja/aspose.slides.export.xaml/ixamloptions) | XAML形式のオプション。 |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
指定された形式で、プレゼンテーションのすべてのスライドをファイルに保存します。

```python
def save(self, fname, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルのパス。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
指定された形式で、プレゼンテーションのすべてのスライドをストリームに保存します。

```python
def save(self, stream, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定された形式と追加オプションで、プレゼンテーションのすべてのスライドをファイルに保存します。

```python
def save(self, fname, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルのパス。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定された形式と追加オプションで、プレゼンテーションのすべてのスライドをストリームに保存します。

```python
def save(self, stream, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 暗号化されたファイルを <br/>            Office 2007-2010 形式以外で保存しようとした場合 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
指定されたスライドを、指定された形式でファイルに保存します。

```python
def save(self, fname, slides, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルのパス。 |
| slides | **List[int]** | 1 から始まるスライドの位置を示す配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメータが None の場合。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメータに無効なページ番号が含まれている場合。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP）。 |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
指定されたスライドを、指定された形式でストリームに保存します。

```python
def save(self, stream, slides, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメータが None の場合。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメータに無効なページ番号が含まれている場合。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP）。 |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定されたスライドを、指定された形式でファイルに保存します。

```python
def save(self, fname, slides, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルのパス。 |
| slides | **List[int]** | 1 から始まるスライドの位置を示す配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメータが None の場合。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメータに無効なページ番号が含まれている場合。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP）。 |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定されたスライドを、指定された形式でストリームに保存します。

```python
def save(self, stream, slides, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| slides | **List[int]** | 1 から始まるスライドの位置を示す配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメータが None の場合。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメータに無効なページ番号が含まれている場合。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP）。 |

### 参照
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions)
* クラス [`IXamlOptions`](/slides/python-net/ja/aspose.slides.export.xaml/ixamloptions)
* 列挙型 [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)