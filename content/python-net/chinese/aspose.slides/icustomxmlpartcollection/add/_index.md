---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icustomxmlpartcollection/add/
weight: 10
---
## add(self, xml_data) {#bytes}
添加新的自定义 xml 部分。

### 返回

已创建自定义 xml 部分。



```python
def add(self, xml_data):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| xml_data | **bytes** | 要添加的新部件的 xml 数据。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlData 为 `None`。 |
| **RuntimeError(Proxy error(ArgumentException))** | xmlData 为空或无效。 |


## add(self, xml_string) {#str}
添加新的自定义 xml 部分。

### 返回

已创建自定义 xml 部分。



```python
def add(self, xml_string):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| xml_string | **str** | 要添加的新部件的 xml 字符串。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | xmlString 为 `None`。 |
| **RuntimeError(Proxy error(ArgumentException))** | xmlString 为空或 xml 数据无效。 |


## add(self, input_stream) {#iorawiobase}
添加新的自定义 xml 部分。

### 返回

已创建自定义 xml 部分。



```python
def add(self, input_stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| input_stream | **io.RawIOBase** | 要添加的新部件的包含 xml 数据的 inputStream。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | inputStream 为 `None`。 |
| **RuntimeError(Proxy error(ArgumentException))** | inputStream 中的数据为空或无效。 |



### 另请参见
* 类 [`ICustomXmlPart`](/slides/python-net/zh/aspose.slides/icustomxmlpart)
* 类 [`ICustomXmlPartCollection`](/slides/python-net/zh/aspose.slides/icustomxmlpartcollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)