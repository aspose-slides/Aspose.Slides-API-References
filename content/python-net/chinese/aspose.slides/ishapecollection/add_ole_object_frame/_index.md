---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
创建一个新的 OLE 对象框并将其添加到形状集合的末尾。

### 返回值

新创建的 [`IOleObjectFrame`](/slides/python-net/zh/aspose.slides/ioleobjectframe)。



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 OLE 框的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框的宽度，单位为点。 |
| height | **float** | 新 OLE 框的高度，单位为点。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 数据信息（[`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo)）。 |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
创建一个新的 OLE 对象框并将其添加到形状集合的末尾。

### 返回值

新创建的 [`IOleObjectFrame`](/slides/python-net/zh/aspose.slides/ioleobjectframe)。



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 OLE 框的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框的宽度，单位为点。 |
| height | **float** | 新 OLE 框的高度，单位为点。 |
| class_name | **str** | OLE 对象的类名。 |
| path | **str** | 链接文件的路径。<br/><br/>此路径会原样存储在演示文稿中。<br/><br/>如果指定了相对路径，在从不同目录打开演示文稿时，文件将无法访问。 |



### 另请参阅
* 类 [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo)
* 类 [`IOleObjectFrame`](/slides/python-net/zh/aspose.slides/ioleobjectframe)
* 类 [`IShapeCollection`](/slides/python-net/zh/aspose.slides/ishapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)