---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: كائن ثابت يمثل مجموعة للقراءة فقط من تأثيرات تحويل الصورة الفعّالة.
type: docs
url: /ar/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

كائن ثابت يمثل مجموعة للقراءة فقط من تأثيرات تحويل الصورة الفعّالة.

--------------------

الاسم IImageTransformOperationCollectionEffectiveData تم تقصيره إلى IImageTransformOCollectionEffectiveData بسبب أن طول أسماء COM لا يمكن أن يكون أكثر من 39.
## المُنشئ

| المُنشئ | الوصف |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يعيد عدد تأثيرات الصورة في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | يعيد العنصر وفق الفهرس. |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة. |
| [iterator()](#iterator--) | يعيد عدّادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مُكرِّر Java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للقراءات المتعددة). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```

### size() {#size--}
```
public final int size()
```

يعيد عدد تأثيرات الصورة في مجموعة. عدد صحيح للقراءة فقط.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```

يعيد العنصر وفق الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - الكائن [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان الكائن المحدد يساوي الكائن الحالي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع الكائن الحالي. |

**الإرجاع:**
boolean - صحيح إذا كان الكائن المحدد يساوي الكائن الحالي؛ وإلا، خطأ.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين، مناسبة للاستخدام في خوارزميات التجزئة وهياكل البيانات مثل جدول التجزئة.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```

يعيد عدّادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - عداد IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```

يعيد مُكرِّر Java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - مُكرِّر java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة للتعبئة. |
| index | int | الموضع الأولي في مصفوفة الوجهة. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للقراءات المتعددة). بوليّن للقراءة فقط.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. كائن للقراءة فقط.

**الإرجاع:**
java.lang.Object