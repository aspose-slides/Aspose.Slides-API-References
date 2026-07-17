---
title: get_InterruptionToken()
second_title: Aspose.Slides C++ API 参考
description: 用于监视中断请求的令牌。
type: docs
weight: 235
url: /zh/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() 方法

用于监视中断请求的令牌。

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## 备注

此令牌管理整个 [IPresentation](../../ipresentation/) 实例的生命周期。任何长时间运行的操作，例如演示文稿加载或保存，都将通过调用 [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) 方法的 [IInterruptionTokenSource](../../iinterruptiontokensource/) 来中断。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IInterruptionToken](../../iinterruptiontoken/)
* 类 [ILoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)