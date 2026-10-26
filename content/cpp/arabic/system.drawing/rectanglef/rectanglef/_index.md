---
title: RectangleF()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ نسخة جديدة من كائن RectangleF يمثل مستطيلًا بإحداثيات X و Y وعرض وارتفاع معدلين إلى 0.
type: docs
weight: 1
url: /ar/system.drawing/rectanglef/rectanglef/
---
## RectangleF::RectangleF() المُنشئ


إنشاء نسخة جديدة من كائن [RectangleF](../) يمثل مستطيلًا بإحداثيات X و Y وعرض وارتفاع مضبوطة على 0.

```cpp
System::Drawing::RectangleF::RectangleF()
```

## RectangleF::RectangleF(float, float, float, float) المُنشئ


إنشاء نسخة جديدة من كائن [RectangleF](../) يمثل مستطيلًا بالإحداثيات المحددة للزاوية العلوية اليسرى وعرضه وارتفاعه.

```cpp
System::Drawing::RectangleF::RectangleF(float x, float y, float width, float height)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| x | **float** | قيمة إحداثي X للزاوية العلوية اليسرى للمستطيل |
| y | **float** | قيمة إحداثي Y للزاوية العلوية اليسرى للمستطيل |
| width | **float** | عرض المستطيل |
| height | **float** | ارتفاع المستطيل |

## RectangleF::RectangleF(const PointF\&, const SizeF\&) المُنشئ


إنشاء نسخة جديدة من كائن [RectangleF](../) يمثل مستطيلًا بإحداثيات زاويته العلوية اليسرى المحددة ككائن من فئة [PointF](../../pointf/) وعرضه وارتفاعه ككائن من فئة [SizeF](../../sizef/).

```cpp
System::Drawing::RectangleF::RectangleF(const PointF &location, const SizeF &size)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| location | const [PointF](../../pointf/)\& | يحدد موضع الزاوية العلوية اليسرى للمستطيل |
| size | const [SizeF](../../sizef/)\& | يحدد عرض وارتفاع المستطيل |

## RectangleF::RectangleF(const Rectangle\&) المُنشئ


إنشاء نسخة جديدة من كائن [RectangleF](../) يمثل المستطيل المكافئ للمستطيل المحدد.

```cpp
System::Drawing::RectangleF::RectangleF(const Rectangle &rect)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | كائن من فئة [Rectangle](../../rectangle/) يحدد موضع وحجم المستطيل الذي سيمثله الكائن المُنشأ |

## انظر أيضًا

* الفئة [RectangleF](../)
* الفئة [PointF](../../pointf/)
* الفئة [SizeF](../../sizef/)
* الفئة [Rectangle](../../rectangle/)
* النطاق [System::Drawing](../../)
* المكتبة [Aspose.Slides](../../../)