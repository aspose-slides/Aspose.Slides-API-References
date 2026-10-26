---
title: GetScriptFont()
second_title: مرجع API Aspose.Slides برای C++
description: نام فونت مرتبط با برچسب اسکریپت خاصی را از تم ارائه دریافت می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) متد

نام فونتی که با برچسب اسکریپت خاصی در تم ارائه مرتبط است را دریافت می‌کند.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | کد اسکریپت BCP-47 (مثلاً "Latn"، "Cyrl"، "Jpan") که برای شناسایی یک سیستم نوشتاری استفاده می‌شود. |

### مقدار بازگشت

نام فونتی که برای اسکریپت مشخص شده استفاده می‌شود، یا **null** اگر اسکریپت تعریف نشده باشد.

## ملاحظات

این مثال نشان می‌دهد چگونه می‌توان فونت اختصاص داده شده به اسکریپت سیریلیک را در تم ارائه بازیابی کرد.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## مراجع

* Class [String](../../../system/string/)
* Class [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)