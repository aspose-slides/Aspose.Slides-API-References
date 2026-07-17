---
title: Warning()
second_title: Aspose.Slides C++ API 参考
description: 回调方法，用于接收警告并决定是否应中止操作。
type: docs
weight: 1
url: /zh/aspose.slides.warnings/iwarningcallback/warning/
---
## IWarningCallback::Warning(System::SharedPtr\<IWarningInfo\>) 方法

回调方法用于接收警告并决定是否应中止操作。

```cpp
virtual ReturnAction Aspose::Slides::Warnings::IWarningCallback::Warning(System::SharedPtr<IWarningInfo> warning)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| warning | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningInfo](../../iwarninginfo/)\> | 要处理的警告。 |

### 返回值

中止决定 [ReturnAction](../../returnaction/)。

## 另请参阅

* Enum [ReturnAction](../../returnaction/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IWarningInfo](../../iwarninginfo/)
* 类 [IWarningCallback](../)
* 命名空间 [Aspose::Slides::Warnings](../../)
* Library [Aspose.Slides](../../../)