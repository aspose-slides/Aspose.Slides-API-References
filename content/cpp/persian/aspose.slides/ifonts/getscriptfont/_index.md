---
title: GetScriptFont()
second_title: Aspose.Slides برای C++ مرجع API
description: نام قلم مرتبط با یک برچسب اسکریپت خاص را از تم ارائه دریافت می‌کند.
type: docs
weight: 92
url: /fa/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) متد

نام قلم مرتبط با یک برچسب اسکریپت خاص را از تم ارائه دریافت می‌کند.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | کد اسکریپت BCP-47 (مانند "Latn"، "Cyrl"، "Jpan") که برای شناسایی یک سیستم نوشتاری استفاده می‌شود. |

### مقدار برگشتی

نام قلم مورد استفاده برای اسکریپت مشخص‌شده، یا **null** اگر اسکریپت تعریف نشده باشد.

## توضیحات

این مثال نشان می‌دهد که چگونه قلم اختصاص‌یافته به اسکریپت سیریلیک را در تم ارائه بازیابی کنید. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [IFonts](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)