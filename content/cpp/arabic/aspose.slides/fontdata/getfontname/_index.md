---
title: GetFontName()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد اسم الخط، مع استبدال إشارة الثيم بخط فعلي يُستخدم.
type: docs
weight: 27
url: /ar/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) طريقة

Returns the font name, replacing theme referrence with an actual font used.

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) الذي يجب أخذ اسم الخط المرتبط بالثيم منه. الأمر متروك للمتصل لتوفير قيمة صحيحة. انظر [IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) |

### قيمة الإرجاع

Font name.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* فئة [FontData](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)