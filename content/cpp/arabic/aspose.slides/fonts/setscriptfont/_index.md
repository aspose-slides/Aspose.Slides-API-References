---
title: SetScriptFont()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُعيّن اسم الخط لعلامة نصية محددة، مما يحدد كيفية عرض النص الخاص بذلك النص في العرض التقديمي.
type: docs
weight: 105
url: /ar/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) طريقة

تعيّن اسم الخط لعلامة نصية محددة، مما يحدد كيفية عرض النص الخاص بذلك النص في العرض التقديمي.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | رمز النص وفق BCP-47 (مثال: "Arab"، "Hebr"، "Hans") الذي يحدد نظام الكتابة. |
| fontName | [System::String](../../../system/string/) | اسم الخط الذي سيُعيّن للنص المحدد. |
## ملاحظات

يوضح هذا المثال كيفية تعيين الخط للنص العربي إلى "Segoe UI":
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [Fonts](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)