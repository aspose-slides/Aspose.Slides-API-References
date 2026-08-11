---
title: SetScriptFont()
second_title: مرجع API Aspose.Slides برای C++
description: یک نام قلم را به برچسب اسکریپت خاصی اختصاص می‌دهد که تعیین می‌کند متن آن اسکریپت در ارائه چگونه رندر شود.
type: docs
weight: 105
url: /fa/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) متد

یک نام قلم را به برچسب اسکریپت خاصی اختصاص می‌دهد که تعیین می‌کند متن آن اسکریپت در ارائه چگونه رندر شود.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | کد اسکریپت BCP-47 (مثلاً "Arab", "Hebr", "Hans") که سیستم نوشتاری را شناسایی می‌کند. |
| fontName | [System::String](../../../system/string/) | نام قلمی که برای اسکریپت مشخص شده اختصاص می‌یابد. |
## ملاحظات

این مثال نشان می‌دهد چگونه قلم برای اسکریپت عربی به "Segoe UI" تنظیم شود: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [Fonts](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)