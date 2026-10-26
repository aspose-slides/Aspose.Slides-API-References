---
title: GetScriptFontMap()
second_title: مرجع API ل Aspose.Slides للغة C++
description: تُرجع قاموسًا يحتوي على جميع تعريفات خطوط النصوص في العرض التقديمي.
type: docs
weight: 79
url: /ar/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() طريقة


تُرجع قاموسًا لجميع تعريفات خطوط النصوص في العرض التقديمي.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### قيمة الإرجاع

قاموس يربط رموز النصوص بأسماء الخطوط.
## الملاحظات




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IDictionary](../../../system.collections.generic/idictionary/)
* فئة [String](../../../system/string/)
* فئة [IFonts](../)
* النطاق [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)