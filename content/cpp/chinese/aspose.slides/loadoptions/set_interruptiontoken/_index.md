---
title: set_InterruptionToken()
second_title: Aspose.Slides for C++ API 参考
description: 用于监视中断请求的令牌。
type: docs
weight: 248
url: /zh/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) 方法

用于监视中断请求的令牌。

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## 备注

此令牌管理整个 [IPresentation](../../ipresentation/) 实例的生命周期。任何长时间运行的操作，例如加载或保存演示文稿，都将通过调用 [InterruptionTokenSource](../../interruptiontokensource/) 的 [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) 方法而被中断。 
## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IInterruptionToken](../../iinterruptiontoken/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)