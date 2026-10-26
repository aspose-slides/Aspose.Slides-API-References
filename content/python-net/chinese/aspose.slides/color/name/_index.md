---
title: name property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/color/name/
weight: 190
---
## name 属性
Gets the name of this color.<br/>            对于已命名的颜色（例如 `Color.red` 这样的已命名常量，或使用 [`from_name`](/slides/python-net/zh/aspose.slides/color/from_name/) 创建的颜色），返回 .NET 名称，例如 `"Red"` 或 `"LightBlue"`。<br/>            对于其他任何颜色，返回 ARGB 值的十六进制小写形式，不带前导零，例如 `"ffff0000"`。 `Color.empty.name` 为 `"0"`。
            只读 **str**.

### 定义:
```python
@property
def name(self):
    ...
```

### 另请参阅
* 类 [`Color`](/slides/python-net/zh/aspose.slides/color)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)