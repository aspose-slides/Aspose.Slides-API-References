---
title: GetScriptFontMap()
second_title: Aspose.Slides برای C++ مرجع API
description: یک دیکشنری از تمام تعریف‌های قلم اسکریپت در ارائه برمی‌گرداند.
type: docs
weight: 79
url: /fa/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() متد


یک دیکشنری از تمام تعریف‌های قلم اسکریپت در ارائه برمی‌گرداند.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### مقدار بازگشت

یک دیکشنری که کدهای اسکریپت را به نام‌های قلم نگاشت می‌کند.
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
* کلاس [Fonts](../)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)