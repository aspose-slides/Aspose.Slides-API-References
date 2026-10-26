---
title: GetScriptFontMap()
second_title: مرجع API Aspose.Slides برای C++
description: تمام تعریف‌های فونت اسکریپت در ارائه را به صورت یک دیکشنری برمی‌گرداند.
type: docs
weight: 79
url: /fa/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() متد

تمام تعاریف فونت اسکریپت در ارائه را به صورت یک دیکشنری برمی‌گرداند.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### مقدار بازگشت

دیکشنری‌ای که کدهای اسکریپت را به نام‌های فونت نگاشت می‌کند.

## توضیحات

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IDictionary](../../../system.collections.generic/idictionary/)
* کلاس [String](../../../system/string/)
* کلاس [IFonts](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)