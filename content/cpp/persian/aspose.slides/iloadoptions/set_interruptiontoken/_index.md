---
title: set_InterruptionToken()
second_title: Aspose.Slides برای C++ مرجع API
description: توکنی برای نظارت بر درخواست‌های قطع.
type: docs
weight: 248
url: /fa/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) متد

توکنی که برای نظارت بر درخواست‌های قطع استفاده می‌شود.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## توضیحات

این توکن عمر کل نمونه [IPresentation](../../ipresentation/) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، با فراخوانی متد [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) از [IInterruptionTokenSource](../../iinterruptiontokensource/) قطع خواهد شد.

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IInterruptionToken](../../iinterruptiontoken/)
* کلاس [ILoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)