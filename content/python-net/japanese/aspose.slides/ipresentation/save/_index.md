---
title: save method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
プレゼンテーションのすべてのスライドを、XAML マークアップを表す一連のファイルに保存します。

```python
def save(self, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ja/aspose.slides.export.xaml/ixamloptions) | XAML 形式のオプション。 |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
指定された形式でプレゼンテーションのすべてのスライドをファイルに保存します。

```python
def save(self, fname, format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されるファイルへのパス。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
指定された形式でプレゼンテーションのすべてのスライドをストリームに保存します。

```python
def save(self, stream, format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定された形式と追加オプションでプレゼンテーションのすべてのスライドをファイルに保存します。

```python
def save(self, fname, format, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されるファイルへのパス。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定された形式と追加オプションでプレゼンテーションのすべてのスライドをストリームに保存します。

```python
def save(self, stream, format, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 暗号化されたファイルを Office 2007-2010 以外の形式で保存しようとした場合 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
指定された形式でプレゼンテーションの特定のスライドをファイルに保存します。

```python
def save(self, fname, slides, format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されるファイルへのパス。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメーターが None のとき。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメーターに無効なページ番号が含まれているとき。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
指定された形式でプレゼンテーションの特定のスライドをストリームに保存します。

```python
def save(self, stream, slides, format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメーターが None のとき。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメーターに無効なページ番号が含まれているとき。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定された形式でプレゼンテーションの特定のスライドをファイルに保存します。

```python
def save(self, fname, slides, format, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| fname | **str** | 作成されるファイルへのパス。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメーターが None のとき。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメーターに無効なページ番号が含まれているとき。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
指定された形式でプレゼンテーションの特定のスライドをストリームに保存します。

```python
def save(self, stream, slides, format, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 出力ストリーム。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| format | [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat) | エクスポートデータの形式。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 追加の形式オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | stream または slides パラメーターが None のとき。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | slides パラメーターに無効なページ番号が含まれているとき。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | サポートされていない SaveFormat が使用された場合（例: PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP）。 |

### 参照
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions)
* クラス [`IXamlOptions`](/slides/python-net/ja/aspose.slides.export.xaml/ixamloptions)
* 列挙型 [`SaveFormat`](/slides/python-net/ja/aspose.slides.export/saveformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)