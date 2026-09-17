---
title: add method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/customxmlpartcollection/add/
weight: 10
---
## add(self, xml_string) {#str}
新しいカスタム XML パートを追加します。

### 戻り値

カスタム XML パートが作成されました。

```python
def add(self, xml_string):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| xml_string | **str** | 追加する新しいパートの XML 文字列。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString は `None` です。 |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString が空であるか、XML データが無効です。 |

## add(self, xml_data) {#bytes}
新しいカスタム XML パートを追加します。

### 戻り値

カスタム XML パートが作成されました。

```python
def add(self, xml_data):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| xml_data | **bytes** | 追加する新しいパートの XML データ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData は `None` です。 |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData が空であるか、無効です。 |

## add(self, input_stream) {#iorawiobase}
新しいカスタム XML パートを追加します。

### 戻り値

カスタム XML パートが作成されました。

```python
def add(self, input_stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | 追加する新しいパートの XML データを含む inputStream。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream は `None` です。 |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream のデータが空であるか、無効です。 |

### 参照
* クラス [`CustomXmlPartCollection`](/slides/python-net/ja/aspose.slides/customxmlpartcollection)
* クラス [`ICustomXmlPart`](/slides/python-net/ja/aspose.slides/icustomxmlpart)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)