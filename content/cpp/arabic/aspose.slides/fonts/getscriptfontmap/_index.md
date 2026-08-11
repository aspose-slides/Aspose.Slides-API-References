---
title: GetScriptFontMap()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إرجاع قاموس يحتوي على جميع تعريفات خطوط النص في العرض التقديمي.
type: docs
weight: 79
url: /ar/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() طريقة

تُرجع قاموسًا يحتوي على جميع تعريفات خطوط النص في العرض التقديمي.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```

### قيمة الإرجاع

قاموس يربط رموز النص بأسماء الخطوط.
## ملاحظات

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## راجع أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IDictionary](../../../system.collections.generic/idictionary/)
* فئة [String](../../../system/string/)
* فئة [Fonts](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)