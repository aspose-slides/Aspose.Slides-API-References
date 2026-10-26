---
title: SendWarning()
second_title: Aspose.Slides for C++ API 参考
description: 如果 receiver 不为 null，则结束对指定接收器的警告，并在接收器决定中止操作时抛出 AbortRequestedException。
type: docs
weight: 27
url: /zh/aspose.slides.warnings/iwarninginfo/sendwarning/
---
## IWarningInfo::SendWarning(System::SharedPtr\<IWarningCallback\>) 方法

如果 receiver 不为 null，则结束对指定 receiver 的警告，并在 receiver 决定中止操作时抛出 AbortRequestedException。

```cpp
virtual void Aspose::Slides::Warnings::IWarningInfo::SendWarning(System::SharedPtr<IWarningCallback> receiver)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| receiver | [System::SharedPtr](../../../system/sharedptr/)\<[IWarningCallback](../../iwarningcallback/)\> | 接收器对象 [IWarningCallback](../../iwarningcallback/) |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IWarningCallback](../../iwarningcallback/)
* 类 [IWarningInfo](../)
* 命名空间 [Aspose::Slides::Warnings](../../)
* 库 [Aspose.Slides](../../../)