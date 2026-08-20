---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: يمثل حجم واتجاه الشريحة.
type: docs
url: /ar/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

يمثل حجم واتجاه الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على أبعاد الشريحة بالنقاط. |
| [getType()](#getType--) | يحصل على نوع حجم الشريحة. |
| [getOrientation()](#getOrientation--) | يحصل على أو يضبط اتجاه الشريحة. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل على أو يضبط اتجاه الشريحة. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | يضبط حجم الشريحة حسب النوع ويُعيد تحجيم المحتوى الموجود. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | يضبط أبعاد الشريحة صراحةً ويُعيد تحجيم المحتوى الموجود. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

يحصل على أبعاد الشريحة بالنقاط.

--------------------

تعيين قيمة جديدة يعيد ضبط خاصية #getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط خاصية #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**الإرجاع:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

يحصل على نوع حجم الشريحة.

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط #getSize.getSize وفقًا للأبعاد المحددة مسبقًا، مع الحفاظ على #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) الحالي.

**الإرجاع:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

يحصل على أو يضبط اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدل عرض وارتفاع الشريحة.

**الإرجاع:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

يحصل على أو يضبط اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدل عرض وارتفاع الشريحة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

يضبط حجم الشريحة حسب النوع ويُعيد تحجيم المحتوى الموجود.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | حجم الشريحة المحدد مسبقًا لتطبيقه. |
| scaleType | int | وضعية تحجيم المحتوى المراد استخدامها. |

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط #getSize.getSize بناءً على النوع المختار، مع الحفاظ على #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

يضبط أبعاد الشريحة صراحةً ويُعيد تحجيم المحتوى الموجود.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض الشريحة الجديد بالنقاط. |
| height | float | ارتفاع الشريحة الجديد بالنقاط. |
| scaleType | int | وضعية تحجيم المحتوى المراد استخدامها. |

--------------------

هذا يعيد ضبط خاصية #getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط {\#getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |