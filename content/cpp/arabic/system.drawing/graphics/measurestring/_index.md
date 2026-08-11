---
title: MeasureString()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: تُرجع حجم السلسلة المحددة عند رسمها باستخدام الخط المحدد وبالصيغة المحددة.
type: docs
weight: 521
url: /ar/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, PointF const&, System::SharedPtr\<StringFormat\> const&) const طريقة

تُرجع حجم السلسلة المحددة عند رسمها باستخدام الخط المحدد وبالصيغة المحددة.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | السلسلة التي يُحسب حجمها |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | الخط المستخدم لرسم السلسلة |
| origin | [PointF](../../pointf/) const\& | يحدد موقع الزاوية العلوية اليسرى للسلسلة |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | يحدد صيغة السلسلة |

### قيمة الإرجاع

كائن [SizeF](../../sizef/) يمثل حجم السلسلة بوحدات القياس المحددة بواسطة خاصية PageUnit لكائن Graphics الحالي.

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, int, System::SharedPtr\<StringFormat\> const&) const طريقة

تُرجع حجم السلسلة المحددة عند رسمها باستخدام الخط المحدد وبالصيغة المحددة.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | السلسلة التي يُحسب حجمها |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | الخط المستخدم لرسم السلسلة |
| width | int | العرض الأقصى للسلسلة |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | يحدد صيغة السلسلة |

### قيمة الإرجاع

كائن [SizeF](../../sizef/) يمثل حجم السلسلة بوحدات القياس المحددة بواسطة خاصية PageUnit لكائن Graphics الحالي.

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&, int\&, int\&) const طريقة

غير مُنفّذ.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const&, System::SharedPtr\<Font\> const&, SizeF const&, System::SharedPtr\<StringFormat\> const&) const طريقة

تُرجع حجم السلسلة المحددة عند رسمها باستخدام الخط المحدد وبالصيغة المحددة.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | السلسلة التي يُحسب حجمها |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | الخط المستخدم لرسم السلسلة |
| layoutArea | [SizeF](../../sizef/) const\& | منطقة التخطيط القصوى للسلسلة |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | يحدد صيغة السلسلة |

### قيمة الإرجاع

كائن [SizeF](../../sizef/) يمثل حجم السلسلة بوحدات القياس المحددة بواسطة خاصية PageUnit لكائن Graphics الحالي.

## انظر أيضاً

* تعريف النوع [SharedPtr](../../../system/sharedptr/)
* الفئة [SizeF](../../sizef/)
* الفئة [String](../../../system/string/)
* الفئة [Font](../../font/)
* الفئة [PointF](../../pointf/)
* الفئة [StringFormat](../../stringformat/)
* الفئة [Graphics](../)
* الفضاء الاسمي [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)