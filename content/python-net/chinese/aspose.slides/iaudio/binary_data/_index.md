---
title: binary_data property
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iaudio/binary_data/
weight: 20
---
## binary_data 属性
返回音频数据的副本。对于大量数据的情况，建议使用 [`IAudio.get_stream`](/slides/python-net/zh/aspose.slides/iaudio/get_stream) 方法，以防止不必要地将音频数据加载到内存中，甚至导致 OutOfMemoryException。只读 **int**[]。

### 定义：
```python
@property
def binary_data(self):
    ...
```


### 另请参见
* 类 [`IAudio`](/slides/python-net/zh/aspose.slides/iaudio)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)