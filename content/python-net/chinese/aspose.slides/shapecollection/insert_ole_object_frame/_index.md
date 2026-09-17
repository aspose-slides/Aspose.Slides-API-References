---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
创建一个新的 OLE 对象框并将其插入到指定索引的形状集合中。

### Returns
新创建的[`IOleObjectFrame`](/slides/python-net/zh/aspose.slides/ioleobjectframe)。

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 在该位置插入 OLE 对象框的零基索引。 |
| x | **float** | 新 OLE 框的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框的宽度，单位为点。 |
| height | **float** | 新 OLE 框的高度，单位为点。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 数据信息 ([`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo))。 |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
创建一个新的 OLE 对象框并将其插入到指定索引的形状集合中。

### Returns
新创建的 OLE 对象框。

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | **int** | 在该位置插入 OLE 对象框的零基索引。 |
| x | **float** | 新 OLE 框的 x 坐标，单位为点。 |
| y | **float** | 新 OLE 框的 y 坐标，单位为点。 |
| width | **float** | 新 OLE 框的宽度，单位为点。 |
| height | **float** | 新 OLE 框的高度，单位为点。 |
| class_name | **str** | OLE 对象的类名。 |
| path | **str** | 链接文件的路径。<br/><br/>此路径以原样存储在演示文稿中。<br/><br/>如果指定了相对路径，则在从不同目录打开演示文稿时，文件将不可访问。 |

### See Also
* 类 [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo)
* 类 [`IOleObjectFrame`](/slides/python-net/zh/aspose.slides/ioleobjectframe)
* 类 [`ShapeCollection`](/slides/python-net/zh/aspose.slides/shapecollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)