---
title: FontFamily()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از کلاس FontFamily می‌سازد که یک خانوادهٔ قلم با نام مشخص‌شده را نشان می‌دهد.
type: docs
weight: 1
url: /fa/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) سازنده

یک نمونه جدید از کلاس [FontFamily](../) که نشان‌دهنده یک خانوادهٔ قلم با نام مشخص است، می‌سازد.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام یک خانوادهٔ قلم |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) سازنده

یک نمونه جدید از [FontFamily](../) را در FontCollection مشخص‌شده با نام داده‌شده می‌سازد.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام یک خانوادهٔ قلم |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollectionی که این نمونه را شامل می‌شود. |

## FontFamily::FontFamily(Text::GenericFontFamilies) سازنده

یک نمونه جدید از [FontFamily](../) را از خانوادهٔ قلم عمومی مشخص شده می‌سازد.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | مقدار GenericFontFamilies برای ساخت [FontFamily](../). |

## مراجع

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [FontFamily](../)
* Class [FontCollection](../../../system.drawing.text/fontcollection/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)