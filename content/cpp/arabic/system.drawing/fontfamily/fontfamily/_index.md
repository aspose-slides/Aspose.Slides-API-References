---
title: FontFamily()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بإنشاء نسخة جديدة من الفئة FontFamily التي تمثل عائلة خطوط بالاسم المحدد.
type: docs
weight: 1
url: /ar/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) منشئ


ينشئ مثالًا جديدًا من الفئة [FontFamily](../) التي تمثل عائلة خطوط بالاسم المحدد.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم عائلة الخطوط |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) منشئ


ينشئ مثالًا جديدًا من [FontFamily](../) في مجموعة الخطوط المحددة بالاسم المحدد.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | اسم عائلة الخطوط |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | مجموعة الخطوط التي تحتوي على هذا المثال. |

## FontFamily::FontFamily(Text::GenericFontFamilies) منشئ


ينشئ مثالًا جديدًا من [FontFamily](../) من عائلة الخطوط العامة المحددة.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | قيمة GenericFontFamilies لإنشاء [FontFamily](../). |

## راجع أيضًا

* تعداد [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [FontFamily](../)
* فئة [FontCollection](../../../system.drawing.text/fontcollection/)
* مساحة اسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)