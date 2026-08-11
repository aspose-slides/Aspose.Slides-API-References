---
title: GetScriptFont()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يحصل على اسم الخط المرتبط بوسم سكريبت محدد من سمة العرض.
type: docs
weight: 92
url: /ar/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) طريقة

يسترجع اسم الخط المرتبط بوسم سكريبت محدد من سمة العرض.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | رمز السكريبت وفق BCP-47 (مثال: "Latn"، "Cyrl"، "Jpan") المستخدم لتحديد نظام كتابة. |

### قيمة الإرجاع

اسم الخط المستخدم للسكريبت المحدد، أو **null** إذا لم يكن السكريبت معرفًا.

## ملاحظات

يوضح هذا المثال كيفية استرجاع الخط المعين للسكريبت السيريلي في سمة العرض. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IFonts](../)
* النطاق [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)