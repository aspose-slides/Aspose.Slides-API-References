---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
将 **System.Collections.Generic.ICollection`1** 的元素复制到 **System.Array**，从特定的 **System.Array** 索引开始。


```python
def copy_to(self, array, array_index):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| array | **List[IBehavior]** | 一维的 **System.Array**，是从 **System.Collections.Generic.ICollection`1** 复制的元素的目标。**System.Array** 必须使用从零开始的索引。 |
| array_index | **int** | 在 `array` 中开始复制的基于零的索引。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` 为 None。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` 小于 0。 |
| **RuntimeError(Proxy error(ArgumentException))** | 源 **System.Collections.Generic.ICollection`1** 中的元素数量大于从 `array_index` 到目标 `array` 末尾的可用空间。 |



### 另请参阅
* 类 [`BehaviorCollection`](/slides/python-net/zh/aspose.slides.animation/behaviorcollection)
* 模块 [`aspose.slides.animation`](/slides/python-net/zh/aspose.slides.animation)
* 库 [`Aspose.Slides`](/slides/python-net)