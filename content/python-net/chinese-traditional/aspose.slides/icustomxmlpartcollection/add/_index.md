---
title: add method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
新增自訂 xml 部分。

### 傳回

已建立自訂 xml 部分。



```python
def add(self, xml_data):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| xml_data | **bytes** | 要新增之新部分的 xml 資料。 |

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData 為 `None`。 |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData 為空或無效。 |


## add(self, xml_string) {#str}
新增自訂 xml 部分。

### 傳回

已建立自訂 xml 部分。



```python
def add(self, xml_string):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| xml_string | **str** | 要新增之新部分的 xml 字串。 |

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString 為 `None`。 |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString 為空或 xml-data 無效。 |


## add(self, input_stream) {#iorawiobase}
新增自訂 xml 部分。

### 傳回

已建立自訂 xml 部分。



```python
def add(self, input_stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | 要新增之新部分的 xml 資料輸入串流。 |

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream 為 `None`。 |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream 中的資料為空或 Sinvalid。 |



### 另請參閱
* 類別 [`ICustomXmlPart`](/slides/python-net/zh-hant/aspose.slides/icustomxmlpart)
* 類別 [`ICustomXmlPartCollection`](/slides/python-net/zh-hant/aspose.slides/icustomxmlpartcollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)