---
title: AddFallBackFonts()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضيف خطًا (أو خطوطًا) جديدة إلى قائمة الخطوط الاحتياطية.
type: docs
weight: 40
url: /ar/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) method

يضيف خطًا(خطوط) جديدة إلى قائمة الخطوط الاحتياطية.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### المعطيات

| معامل | نوع | وصف |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | اسم الخط أو الأسماء (مفصولة بفواصل) للاستخدام كخط احتياطي |
## الملاحظات

```cpp
//إنشاء مثال جديد من FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//إضافة الخط الثاني إلى القاعدة
newRule->AddFallBackFonts(u"MS Gothic");
//إضافة الخطين الثالث والرابع إلى القاعدة
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) method

يضيف خطوطًا جديدة إلى قائمة الخطوط الاحتياطية.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### المعطيات

| معامل | نوع | وصف |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | اسم الخط أو الأسماء (مفصولة بفواصل) للاستخدام كخط احتياطي |
## الملاحظات

```cpp
//إنشاء مثال جديد من FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//إضافة ثلاثة خطوط أخرى إلى القاعدة
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## راجع أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)