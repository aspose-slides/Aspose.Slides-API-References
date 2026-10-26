---
title: SlideSize
second_title: Aspose.Slides لنظام Android عبر مرجع واجهة برمجة تطبيقات Java
description: يمثل حجم واتجاه الشريحة.
type: docs
url: /ar/com.aspose.slides/slidesize/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

يمثل حجم واتجاه الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSize()](#getSize--) | يحصل على أبعاد الشريحة بالنقاط. |
| [getType()](#getType--) | يحصل على نوع حجم الشريحة. |
| [getOrientation()](#getOrientation--) | يحصل أو يعيّن اتجاه الشريحة. |
| [setOrientation(int value)](#setOrientation-int-) | يحصل أو يعيّن اتجاه الشريحة. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | يضبط حجم الشريحة حسب النوع ويقوّم المحتوى الموجود. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | يضبط أبعاد الشريحة صراحةً ويقوّم المحتوى الموجود. |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

يحصل على أبعاد الشريحة بالنقاط.

--------------------

تعيين قيمة جديدة يعيد تعيين خاصية \#getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط خاصية \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**القيمة المرجعة:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

يحصل على نوع حجم الشريحة.

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط \#getSize.getSize وفقًا للأبعاد المحددة مسبقًا، مع الحفاظ على \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) الحالي.

**القيمة المرجعة:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

يحصل أو يعيّن اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدل عرض وارتفاع الشريحة.

**القيمة المرجعة:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

يحصل أو يعيّن اتجاه الشريحة.

--------------------

تغيير هذه القيمة يبدل عرض وارتفاع الشريحة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

يضبط حجم الشريحة حسب النوع ويقوّم المحتوى الموجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | int | حجم الشريحة المحدد مسبقًا للتطبيق. |
| scaleType | int | وضع مقياس المحتوى للاستخدام. |

--------------------

تعيين أي قيمة غير [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) يضبط \#getSize.getSize بناءً على النوع المختار، مع الحفاظ على \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

يضبط أبعاد الشريحة صراحةً ويقوّم المحتوى الموجود.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض الشريحة الجديد بالنقاط. |
| height | float | ارتفاع الشريحة الجديد بالنقاط. |
| scaleType | int | وضع مقياس المحتوى للاستخدام. |

--------------------

هذا يعيد تعيين خاصية \#getType.getType إلى [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) ويضبط خاصية \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |