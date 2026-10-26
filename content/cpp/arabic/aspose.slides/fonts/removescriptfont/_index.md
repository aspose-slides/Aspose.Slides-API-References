---
title: RemoveScriptFont()
second_title: مرجع API Aspose.Slides للغة C++
description: يزيل إعداد الخط المرتبط بعلامة نصية معينة من مجموعة خطوط السمة.
type: docs
weight: 118
url: /ar/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) طريقة

يزيل إعداد الخط المرتبط بعلامة برنامج نصي محددة من مجموعة خطوط المظهر.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | رمز البرنامج النصي BCP-47 الذي يجب إزالة إعداد الخط الخاص به. |
## ملاحظات

هذا المثال يوضح كيفية إزالة تعيين الخط للكتابة العبرية:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [Fonts](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)