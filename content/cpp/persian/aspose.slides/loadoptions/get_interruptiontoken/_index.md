---
title: get_InterruptionToken()
second_title: مرجع API Aspose.Slides برای C++
description: توکن برای نظارت بر درخواست‌های قطع.
type: docs
weight: 235
url: /fa/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() متد

توکن برای نظارت بر درخواست‌های قطع.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## توضیحات

این توکن دورهٔ حیات کامل نمونهٔ [IPresentation](../../ipresentation/) را مدیریت می‌کند. هر عملیات طولانی‌مدتی، مانند بارگذاری یا ذخیره‌سازی ارائه، توسط فراخوانی متد [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) از [InterruptionTokenSource](../../interruptiontokensource/) متوقف خواهد شد.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IInterruptionToken](../../iinterruptiontoken/)
* کلاس [LoadOptions](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)