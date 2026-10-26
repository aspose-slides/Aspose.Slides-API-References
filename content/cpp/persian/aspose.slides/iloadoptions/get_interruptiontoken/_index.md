---
title: get_InterruptionToken()
second_title: مرجع API Aspose.Slides برای C++
description: توکنی برای نظارت بر درخواست‌های قطع.
type: docs
weight: 235
url: /fa/aspose.slides/iloadoptions/get_interruptiontoken/
---
## متد ILoadOptions::get_InterruptionToken()

توکنی برای نظارت بر درخواست‌های قطع.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## توضیحات

این توکن تمام دورهٔ حیات نمونهٔ [IPresentation](../../ipresentation/) را مدیریت می‌کند. هر عمل طولانی-مدتی، مانند بارگذاری یا ذخیره‌سازی ارائه، از طریق فراخوانی متد [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) از [IInterruptionTokenSource](../../iinterruptiontokensource/) قطع خواهد شد.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IInterruptionToken](../../iinterruptiontoken/)
* کلاس [ILoadOptions](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)