---
title: set_InterruptionToken()
second_title: راهنمای API Aspose.Slides برای C++
description: توکنی برای نظارت بر درخواست‌های قطع.
type: docs
weight: 248
url: /fa/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) متد

توکنی برای نظارت بر درخواست‌های قطع.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## ملاحظات

این توکن کل زمان‌زیستی نمونه [IPresentation](../../ipresentation/) را مدیریت می‌کند. هر عملیات طولانی‌مدت، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) از [InterruptionTokenSource](../../interruptiontokensource/) متوقف خواهد شد.

## مراجع

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IInterruptionToken](../../iinterruptiontoken/)
* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)