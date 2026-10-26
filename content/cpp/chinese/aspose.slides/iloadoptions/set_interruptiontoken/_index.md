---
title: set_InterruptionToken()
second_title: Aspose.Slides C++ API 参考
description: 用于监视中断请求的令牌。
type: docs
weight: 248
url: /zh/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) 方法

用于监视中断请求的令牌。

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## 备注

此令牌管理整个 [IPresentation](../../ipresentation/) 实例的生命周期。任何长时间运行的操作，例如演示文稿加载或保存，都会通过调用 [IInterruptionTokenSource](../../iinterruptiontokensource/) 的 [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) 方法而被中断。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IInterruptionToken](../../iinterruptiontoken/)
* 类 [ILoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)