---
title: GetScriptFont()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحصل على اسم الخط المرتبط بعلامة نصية محددة من سمة العرض التقديمي.
type: docs
weight: 92
url: /ar/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) الطريقة

Gets the font name associated with a specific script tag from the presentation theme.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```

### الوسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | رمز البرنامج النصي BCP-47 (مثل "Latn", "Cyrl", "Jpan") يُستخدم لتحديد نظام كتابة. |

### قيمة الإرجاع

اسم الخط المستخدم للبرنامج النصي المحدد، أو **null** إذا لم يتم تعريف البرنامج النصي.

## ملاحظات

يوضح هذا المثال كيفية استرجاع الخط المخصص للبرنامج النصي السيريلي في سمة العرض التقديمي. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [Fonts](../)
* المساحة الاسمية [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)