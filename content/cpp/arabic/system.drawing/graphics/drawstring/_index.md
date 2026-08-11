---
title: DrawString()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: ترسم السلسلة المحددة في الموقع المحدد باستخدام الخط والفرشاة المحددين.
type: docs
weight: 365
url: /ar/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) الطريقة

ترسم السلسلة المحددة في الموضع المحدد باستخدام الخط والفرشاة المحددين.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | السلسلة التي سيتم رسمها |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | خط للاستخدام |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | كائن [Brush](../../brush/) للاستخدام في الرسم |
| topLeft | [PointF](../../pointf/) | يحدد موقع الزاوية العليا اليسرى للسلسلة المرسومة |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | يحدد تنسيق السلسلة |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) الطريقة

ترسم السلسلة المحددة داخل المستطيل المحدد باستخدام الخط والفرشاة المحددين.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | السلسلة التي سيتم رسمها |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | خط للاستخدام |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | كائن [Brush](../../brush/) للاستخدام في الرسم |
| layoutRectangle | [RectangleF](../../rectanglef/) | يحدد المستطيل الذي سيتم رسم السلسلة فيه |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | يحدد تنسيق السلسلة |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) الطريقة

ترسم السلسلة المحددة في الموضع المحدد باستخدام الخط والفرشاة المحددين.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | السلسلة التي سيتم رسمها |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | خط للاستخدام |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | كائن [Brush](../../brush/) للاستخدام في الرسم |
| x | **float** | إحداثي X لموقع الزاوية العليا اليسرى للسلسلة المرسومة |
| y | **float** | إحداثي Y لموقع الزاوية العليا اليسرى للسلسلة المرسومة |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | يحدد تنسيق السلسلة |

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [Font](../../font/)
* فئة [Brush](../../brush/)
* فئة [PointF](../../pointf/)
* فئة [StringFormat](../../stringformat/)
* فئة [Graphics](../)
* فئة [RectangleF](../../rectanglef/)
* النطاق [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)