---
title: from_name method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
根据指定的预定义颜色名称创建颜色。<br/>查找不区分大小写，并忽略下划线和空格：`"LightBlue"`、`"lightblue"` 和 `"light_blue"` 都解析为 `Color.light_blue`。请参阅 [`Color`](/slides/python-net/zh/aspose.slides/color) 类页面以获取预定义颜色列表。

### 返回

命名的颜色。

```python
@staticmethod
def from_name(name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | **str** | 一个字符串，表示预定义颜色的名称。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **ValueError** | 该名称不是预定义颜色的名称。 |
| **TypeError** | 该名称不是字符串。 |

### 参见
* 类 [`Color`](/slides/python-net/zh/aspose.slides/color)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)