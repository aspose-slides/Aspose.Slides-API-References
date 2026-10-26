---
title: AddFallBackFonts()
second_title: Aspose.Slides مرجع API للغة C++
description: يضيف خطًا (خطوطًا) جديدًا إلى قائمة خطوط FallBack.
type: docs
weight: 79
url: /ar/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) طريقة

يضيف خطًا (خطوطًا) جديدًا إلى قائمة خطوط FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### وسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | اسم الخط أو الأسماء (مفصولة بفواصل) للـ FallBack |
## ملاحظات

```cpp
// إنشاء نسخة جديدة من FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//أضف خطًا ثانيًا إلى القاعدة
newRule->AddFallBackFonts(u"MS Gothic");
//أضف خطًا ثالثًا ورابعًا إلى القاعدة
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) طريقة

يضيف خطوطًا جديدة إلى قائمة خطوط FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### وسائط

| معامل | نوع | الوصف |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | اسم الخط أو الأسماء (مفصولة بفواصل) للـ FallBack |
## ملاحظات

```cpp
//إنشاء نسخة جديدة من FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//إضافة ثلاثة خطوط أخرى إلى القاعدة
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [FontFallBackRule](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)