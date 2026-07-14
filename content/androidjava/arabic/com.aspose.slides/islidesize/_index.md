---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /ar/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

يمثل حجم واتجاه الشريحة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على أبعاد الشريحة بالنقاط. |
| [getType()](#getType--) | يحصل على نوع حجم الشريحة. |
| [getOrientation()](#getOrientation--) | يحصل على أو يضبط اتجاه الشريحة. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل على أو يضبط اتجاه الشريحة. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | يضبط حجم الشريحة حسب النوع ويقيس المحتوى الموجود. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | يضبط أبعاد الشريحة صراحةً ويقيس المحتوى الموجود. |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

يحصل على أبعاد الشريحة بالنقاط.

--------------------

تعيين قيمة جديدة يعيد تعيين خاصية \#getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**القيمة المرجعة:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

يحصل على نوع حجم الشريحة.

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط \#getSize.getSize وفقًا للأبعاد المعرفة مسبقًا، مع الحفاظ على \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**القيمة المرجعة:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

يحصل على أو يضبط اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدل العرض والارتفاع للشريحة.

**القيمة المرجعة:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

يحصل على أو يضبط اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدل العرض والارتفاع للشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

يضبط حجم الشريحة حسب النوع ويقيس المحتوى الموجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | حجم الشريحة المحدد مسبقًا للتطبيق. |
| scaleType | int | وضع مقياس المحتوى المراد استخدامه.

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط \#getSize.getSize بناءً على النوع المختار، مع الحفاظ على \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

يضبط أبعاد الشريحة صراحةً ويقيس المحتوى الموجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | float | العرض الجديد للشريحة، بالنقاط. |
| height | float | الارتفاع الجديد للشريحة، بالنقاط. |
| scaleType | int | وضع مقياس المحتوى المراد استخدامه.

--------------------

هذا يعيد تعيين خاصية \#getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |