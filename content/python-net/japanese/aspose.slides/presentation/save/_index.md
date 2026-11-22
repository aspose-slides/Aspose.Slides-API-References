---
title: save method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentation/save/
weight: 100
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
プレゼンテーションのすべてのスライドを、XAML マークアップを表す一連のファイルに保存します。

```python
def save(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ja/aspose.slides.export.xaml/ixamloptions) | XAML 形式オプション。 |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
プレゼンテーションのすべてのスライドを、指定された形式のファイルに保存します。

```python
def save(self, fname, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルへのパス。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
プレゼンテーションのすべてのスライドを、指定された形式のストリームに保存します。

```python
def save(self, stream, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) |  |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
プレゼンテーションのすべてのスライドを、指定された形式と追加オプションでストリームに保存します。

```python
def save(self, stream, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 暗号化されたファイルを <br/>            Office 2007-2010 以外の形式で保存しようとした場合 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
指定したスライドをページ番号を保持したまま、指定された形式のファイルに保存します。

```python
def save(self, fname, slides, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルへのパス。 |
| slides | **List[int]** | スライド位置の配列、1 から開始。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | ストリームまたは slides パラメータが None の場合。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメータに無効なページ番号が含まれている場合。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合 (例: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP)。 |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
指定したスライドをページ番号を保持したまま、指定された形式のストリームに保存します。

```python
def save(self, stream, slides, format):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| slides | **List[int]** | スライド位置の配列、1 から開始。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定したスライドをページ番号を保持したまま、指定された形式のファイルに保存します。

```python
def save(self, fname, slides, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されたファイルへのパス。 |
| slides | **List[int]** | スライド位置の配列、1 から開始。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定したスライドをページ番号を保持したまま、指定された形式のストリームに保存します。

```python
def save(self, stream, slides, format, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| slides | **List[int]** | スライド位置の配列、1 から開始。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートされたデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | ストリームまたは slides パラメータが None の場合。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメータに無効なページ番号が含まれている場合。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合 (例: PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP)。 |

### 参照
* クラス [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions)
* クラス [`IXamlOptions`](/slides/python-net/ja/aspose.slides.export.xaml/ixamloptions)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* 列挙体 [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)