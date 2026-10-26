---
title: from_rgb method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/color/from_rgb/
weight: 50
---
## from_rgb(r, g, b) {#int-int-int}
根据指定的红色、绿色和蓝色值创建不透明颜色（alpha 为 255）。

### 返回值

根据指定值创建的颜色。

```python
@staticmethod
def from_rgb(r, g, b):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| r | **int** | 红色分量值。有效值范围为 0 到 255。 |
| g | **int** | 绿色分量值。有效值范围为 0 到 255。 |
| b | **int** | 蓝色分量值。有效值范围为 0 到 255。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 某个分量值小于 0 或大于 255。 |

### 另请参阅
* 类 [`Color`](/slides/python-net/zh/aspose.slides/color)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)