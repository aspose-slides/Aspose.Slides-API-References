---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
将 **System.Collections.Generic.ICollection`1** 的元素复制到 **System.Array**，从特定的 **System.Array** 索引开始。


```python
def copy_to(self, array, array_index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| array | **List[IPortion]** | 从 **System.Collections.Generic.ICollection`1** 复制的元素的目标的一维 **System.Array**。**System.Array** 必须使用零基索引。 |
| array_index | **int** | 在 `array` 中开始复制的零基索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` 为 None。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 小于 0。 |
| **RuntimeError(Proxy error(ArgumentException))** | 源 **System.Collections.Generic.ICollection`1** 中的元素数量大于从 `array_index` 到目标 `array` 末端可用的空间。 |



### 另见
* 类 [`PortionCollection`](/slides/python-net/zh/aspose.slides/portioncollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)