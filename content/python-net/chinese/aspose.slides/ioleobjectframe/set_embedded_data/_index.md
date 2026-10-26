---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
设置有关 OLE 嵌入数据的信息。


```python
def set_embedded_data(self, embedded_data):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo) | 嵌入数据 [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo) |

### 备注

此方法更改对象的属性以反映新数据，并将 IsObjectLink 标志设置为 false，表明 OLE 对象是嵌入的。

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 当 embeddedData 参数为 None 时。 |



### 参见
* 类 [`IOleEmbeddedDataInfo`](/slides/python-net/zh/aspose.slides/ioleembeddeddatainfo)
* 类 [`IOleObjectFrame`](/slides/python-net/zh/aspose.slides/ioleobjectframe)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)