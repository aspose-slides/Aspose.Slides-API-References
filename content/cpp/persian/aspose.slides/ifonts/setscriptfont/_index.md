---
title: SetScriptFont()
second_title: Aspose.Slides برای C++ - مرجع API
description: یک نام قلم را به یک برچسب اسکریپت خاص اختصاص می‌دهد که تعیین می‌کند متن آن اسکریپت چگونه در ارائه رندر شود.
type: docs
weight: 105
url: /fa/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) method

یک نام قلم را به یک برچسب اسکریپت خاص اختصاص می‌دهد که تعیین می‌کند متن آن اسکریپت چگونه در ارائه رندر شود.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | کد اسکریپت BCP-47 (مثلاً "Arab", "Hebr", "Hans") که سیستم نوشتاری را شناسایی می‌کند. |
| fontName | [System::String](../../../system/string/) | نام قلمی که باید به اسکریپت مشخص‌شده اختصاص داده شود. |
## توضیحات

این مثال نشان می‌دهد چگونه قلم برای اسکریپت عربی به "Segoe UI" تنظیم شود:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## منابع مرتبط

* کلاس [String](../../../system/string/)
* کلاس [IFonts](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)