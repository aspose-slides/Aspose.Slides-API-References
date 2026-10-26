---
title: RemoveScriptFont()
second_title: Aspose.Slides برای C++ مرجع API
description: تنظیمات قلم مرتبط با یک برچسب اسکریپت خاص را از مجموعه قلم‌های تم حذف می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) متد

تنظیمات قلم مربوط به یک برچسب اسکریپت خاص را از مجموعه قلم‌های تم حذف می‌کند.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | کد اسکریپت BCP-47 که تنظیمات قلم آن باید حذف شود. |
## ملاحظات



این مثال نشان می‌دهد چگونه نگاشت قلم برای اسکریپت عبری را حذف کنیم: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [Fonts](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)