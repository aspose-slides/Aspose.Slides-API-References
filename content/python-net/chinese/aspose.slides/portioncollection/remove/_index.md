---
title: remove method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/portioncollection/remove/
weight: 70
---
## remove(self, item) {#iportion}
移除特定对象在 **System.Collections.Generic.ICollection`1** 中的第一次出现。

### 返回值

如果 `item` 已成功从 **System.Collections.Generic.ICollection`1** 中移除，则返回 true；否则返回 false。如果在原始 **System.Collections.Generic.ICollection`1** 中未找到 `item`，此方法也返回 false。

```python
def remove(self, item):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| item | [`IPortion`](/slides/python-net/zh/aspose.slides/iportion) | 要从 **System.Collections.Generic.ICollection`1** 中移除的对象。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | **System.Collections.Generic.ICollection`1** 是只读的。 |

### 另见
* 类 [`IPortion`](/slides/python-net/zh/aspose.slides/iportion)
* 类 [`PortionCollection`](/slides/python-net/zh/aspose.slides/portioncollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)