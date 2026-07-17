---
title: PersistenceType
second_title: Aspose.Slides for C++ API 参考
description: 指定用于存储 ActiveX 控件属性的方法。
type: docs
weight: 6189
url: /zh/aspose.slides/persistencetype/
---
## PersistenceType 枚举

指定用于存储 ActiveX 控件属性的方法。

```cpp
enum class PersistenceType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| NotDefined | -1 | 未指定持久化 ID。 |
| PersistPropertyBag | 0 | 指定 ActiveX 控件使用基于属性包的持久化方式。基于属性包的持久化通过一组名称和值对来存储 ActiveX 控件持久化的数据。 |
| PersistStream | 1 | 指定 ActiveX 控件使用基于流的持久化方式，该方式不支持将 ActiveX 控件初始化为默认状态。 |
| PersistStreamInit | 2 | 指定 ActiveX 控件使用基于流的持久化方式，该方式支持将 ActiveX 控件初始化为默认状态。 |
| PersistStorage | 3 | 指定 ActiveX 控件使用基于存储的持久化方式。 |

## 另请参见

* 命名空间 [Aspose::Slides](../)
* 库 [Aspose.Slides](../../)