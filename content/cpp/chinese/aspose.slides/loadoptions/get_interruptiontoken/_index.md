---
title: get_InterruptionToken()
second_title: Aspose.Slides C++ API 参考
description: 用于监视中断请求的令牌。
type: docs
weight: 235
url: /zh/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() 方法


用于监视中断请求的令牌。

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## 备注


此令牌管理整个 [IPresentation](../../ipresentation/) 实例的生命周期。任何长时间运行的操作，例如加载或保存演示文稿，都将在调用 [InterruptionTokenSource](../../interruptiontokensource/) 的 [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) 方法时被中断。 
## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IInterruptionToken](../../iinterruptiontoken/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)