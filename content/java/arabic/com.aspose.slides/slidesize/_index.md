---
title: SlideSize
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل حجم واتجاه الشريحة.
type: docs
url: /ar/com.aspose.slides/slidesize/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

يمثل حجم واتجاه الشريحة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على أبعاد الشريحة بالنقاط. |
| [getType()](#getType--) | يحصل على نوع حجم الشريحة. |
| [getOrientation()](#getOrientation--) | يحصل أو يضبط اتجاه الشريحة. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل أو يضبط اتجاه الشريحة. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | يضبط حجم الشريحة حسب النوع ويُقِّم المحتوى الحالي. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | يضبط أبعاد الشريحة صراحةً ويُقِّم المحتوى الحالي. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


يحصل على أبعاد الشريحة بالنقاط.

--------------------

تعيين قيمة جديدة يعيد تعيين الخاصية \#getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط الخاصية \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**الإرجاع:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```


يحصل على نوع حجم الشريحة.

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط \#getSize.getSize وفقًا للأبعاد المحددة مسبقًا، مع الحفاظ على \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) الحالي.

**الإرجاع:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


يحصل أو يضبط اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدّل عرض الشريحة وارتفاعها.

**الإرجاع:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


يحصل أو يضبط اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدّل عرض الشريحة وارتفاعها.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


يضبط حجم الشريحة حسب النوع ويُقِّم المحتوى الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | حجم الشريحة المحدد مسبقًا لتطبيقه. |
| scaleType | int | وضعية تحجيم المحتوى المستخدمة. |

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط \#getSize.getSize بناءً على النوع المحدد، مع الحفاظ على \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


يضبط أبعاد الشريحة صراحةً ويُقِّم المحتوى الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض الشريحة الجديد بالنقاط. |
| height | float | ارتفاع الشريحة الجديد بالنقاط. |
| scaleType | int | وضعية تحجيم المحتوى المستخدمة. |

--------------------

هذا يعيد تعيين الخاصية \#getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط الخاصية \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |