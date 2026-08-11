---
title: SetScriptFont()
second_title: Aspose.Slides لـ C++ مرجع API
description: يُعيّن اسم خط إلى علامة سكريبت محددة، والتي تحدد كيفية عرض نص ذلك السكريبت في العرض التقديمي.
type: docs
weight: 105
url: /ar/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) طريقة

يُعيّن اسم خط إلى علامة سكريبت محددة، التي تحدد كيفية عرض نص ذلك السكريبت في العرض التقديمي.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | رمز السكريبت BCP-47 (مثال: "Arab", "Hebr", "Hans") الذي يحدد نظام الكتابة. |
| fontName | [System::String](../../../system/string/) | اسم الخط الذي سيُعيّن للسكريبت المحدد. |
## ملاحظات

يوضح هذا المثال كيفية ضبط الخط للسكريبت العربي إلى "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IFonts](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)