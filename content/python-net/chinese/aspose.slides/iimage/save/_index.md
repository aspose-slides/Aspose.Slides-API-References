---
title: save method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
将图像保存到文件。


```python
def save(self, filename):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| filename | **str** | 保存图像的文件路径。 |


## save(self, filename, format) {#str-imageformat}
将图像以指定格式保存到文件。


```python
def save(self, filename, format):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| filename | **str** | 保存图像的文件路径。 |
| format | [`ImageFormat`](/slides/python-net/zh/aspose.slides/imageformat) | 图像格式。 |


## save(self, stream, format) {#iorawiobase-imageformat}
将图像以指定格式保存到流中。


```python
def save(self, stream, format):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 图像将被保存的流。 |
| format | [`ImageFormat`](/slides/python-net/zh/aspose.slides/imageformat) | 图像格式。 |


## save(self, filename, format, quality) {#str-imageformat-int}
将图像以指定的格式和质量保存到文件。


```python
def save(self, filename, format, quality):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| filename | **str** | 保存图像的文件路径。 |
| format | [`ImageFormat`](/slides/python-net/zh/aspose.slides/imageformat) | 图像格式。 |
| quality | **int** | 保存图像的质量（0 到 100）。  <br/><br/>            此参数仅在 [`ImageFormat.JPEG`](/slides/python-net/zh/aspose.slides/imageformat/JPEG) 中生效；对所有其他格式均被忽略。 |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
将图像以指定的格式和质量保存到流中。


```python
def save(self, stream, format, quality):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 图像将被保存的流。 |
| format | [`ImageFormat`](/slides/python-net/zh/aspose.slides/imageformat) | 图像格式。 |
| quality | **int** | 保存图像的质量（0 到 100）。  <br/><br/>            此参数仅在 [`ImageFormat.JPEG`](/slides/python-net/zh/aspose.slides/imageformat/JPEG) 中生效；对所有其他格式均被忽略。 |



### 另见
* 类 [`IImage`](/slides/python-net/zh/aspose.slides/iimage)
* 枚举 [`ImageFormat`](/slides/python-net/zh/aspose.slides/imageformat)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)