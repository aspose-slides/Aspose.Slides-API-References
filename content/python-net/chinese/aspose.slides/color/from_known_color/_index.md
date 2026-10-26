---
title: from_known_color method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
从指定的预定义颜色创建颜色。<br/>这是获取系统颜色（例如 `KnownColor.CONTROL`）的唯一方法：系统颜色未作为 `Color` 属性公开，因为其值取决于桌面主题，因此需从库运行时读取。

### 返回值

此方法创建的颜色。

```python
@staticmethod
def from_known_color(known_color):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| known_color | **KnownColor** | `KnownColor` 枚举的一个元素（映射 .NET `System.Drawing.KnownColor` 的 `IntEnum`）或其整数值。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 该值不是有效的 `KnownColor` 成员。 |

### 另见
* 类 [`Color`](/slides/python-net/zh/aspose.slides/color)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)