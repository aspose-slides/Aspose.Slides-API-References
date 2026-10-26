---
title: RemoveScriptFont()
second_title: Aspose.Slides لمرجع API للغة C++
description: يزيل إعداد الخط المرتبط بعلامة نصية محددة من مجموعة خطوط السمة.
type: docs
weight: 118
url: /ar/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) طريقة

يزيل إعداد الخط المرتبط بعلامة النص البرمجي المحددة من مجموعة خطوط السمة.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | رمز البرنامج النصي BCP-47 الذي ينبغي إزالة إعداد الخط الخاص به. |
## ملاحظات

يوضح هذا المثال كيفية إزالة تعيين الخط للنص البرمجي العبري:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## انظر أيضاً

* الفئة [String](../../../system/string/)
* الفئة [IFonts](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)