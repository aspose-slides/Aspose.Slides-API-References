---
title: RemoveScriptFont()
second_title: Aspose.Slides برای C++ مرجع API
description: تنظیم فونت مرتبط با یک برچسب اسکریپت خاص را از مجموعه فونت‌های تم حذف می‌کند.
type: docs
weight: 118
url: /fa/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) متد

تنظیم فونت مرتبط با یک برچسب اسکریپت خاص را از مجموعه فونت‌های تم حذف می‌کند.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | کد اسکریپت BCP-47 که تنظیم فونت آن باید حذف شود. |
## مراجع

این مثال نشان می‌دهد چگونه نگاشت فونت برای اسکریپت عبری حذف می‌شود: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [IFonts](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)