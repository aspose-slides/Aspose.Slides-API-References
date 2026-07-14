---
title: SizeF
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: فئة لوصف أبعاد العرض والارتفاع بوحدة عشوائية باستخدام قيم ذات نقطة عائمة.
type: docs
url: /ar/com.aspose.slides.android/sizef/
---
**الوراثة:**
java.lang.Object
```
public class SizeF
```

فئة لوصف أبعاد العرض والارتفاع بوحدة عشوائية باستخدام قيم ذات نقطة عائمة.
## المنشئون

| المنشئ | الوصف |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | إنشاء مثيل جديد من SizeF. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getWidth()](#getWidth--) | إرجاع عرض الحجم. |
| [getHeight()](#getHeight--) | إرجاع ارتفاع الحجم. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحقق مما إذا كان هذا الحجم مساويًا لحجم آخر. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | إرجاع الحجم على شكل سلسلة بالصيغة "WxH" |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

إنشاء مثيل جديد من SizeF.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| width | float | عرض الحجم |
| height | float | ارتفاع الحجم |

### getWidth() {#getWidth--}
```
public float getWidth()
```

إرجاع عرض الحجم.

**الإرجاع:**
float - العرض
### getHeight() {#getHeight--}
```
public float getHeight()
```

إرجاع ارتفاع الحجم.

**الإرجاع:**
float - الارتفاع
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

تحقق مما إذا كان هذا الحجم مساويًا لحجم آخر.

يكون الحجمان متساويين إذا وفقط إذا كان كلا عرضيهما وارتفاعيهما متطابقين.

لهذا الغرض، تُعتبر قيم العرض/الارتفاع من نوع float متساوية إذا وفقط إذا أرجعت الدالة Float\#floatToIntBits(float).floatToIntBits(float) قيمة int متطابقة عند تطبيقها على كلٍ منهما.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object |  |
**الإرجاع:**
boolean -  true  إذا كانت الكائنات متساوية،  false  وإلا
### hashCode() {#hashCode--}
```
public int hashCode()
```

**الإرجاع:**
int
### toString() {#toString--}
```
public String toString()
```

إرجاع الحجم على شكل سلسلة بالصيغة "WxH"

**الإرجاع:**
java.lang.String - تمثيل السلسلة لل حجم