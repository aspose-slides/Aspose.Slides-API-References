---
title: ImageTransformOCollectionEffectiveData
second_title: Aspose.Slides لمرجع API لجافا
description: كائن غير قابل للتغيير يمثل مجموعة للقراءة فقط من تأثيرات تحويل الصورة الفعالة.
type: docs
url: /ar/com.aspose.slides/imagetransformocollectioneffectivedata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IImageTransformOCollectionEffectiveData](../../com.aspose.slides/iimagetransformocollectioneffectivedata)
```
public class ImageTransformOCollectionEffectiveData implements IEffectiveData, IImageTransformOCollectionEffectiveData
```

كائن غير قابل للتعديل يمثل مجموعة قراءة فقط لتأثيرات تحويل الصورة الفعالة.

--------------------

الاسم IImageTransformOperationCollectionEffectiveData تم تقصيره إلى IImageTransformOCollectionEffectiveData لأن طول أسماء COM لا يمكن أن يتجاوز 39.
## المنشئات

| Constructor | Description |
| --- | --- |
| [ImageTransformOCollectionEffectiveData()](#ImageTransformOCollectionEffectiveData--) |  |
## الطرق

| Method | Description |
| --- | --- |
| [size()](#size--) | إرجاع عدد تأثيرات الصورة في مجموعة. |
| [get_Item(int index)](#get-Item-int-) | إرجاع عنصر بحسب الفهرس. |
| [equals(Object obj)](#equals-java.lang.Object-) | تحديد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع محدد، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البيانات مثل جدول التجزئة. |
| [iterator()](#iterator--) | إرجاع تعداد (enumerator) يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مكرر جافا (java iterator) للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر التزامن. |
### ImageTransformOCollectionEffectiveData() {#ImageTransformOCollectionEffectiveData--}
```
public ImageTransformOCollectionEffectiveData()
```


### size() {#size--}
```
public final int size()
```


إرجاع عدد تأثيرات الصورة في مجموعة. عدد صحيح للقراءة فقط.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IEffectEffectiveData get_Item(int index)
```


إرجاع عنصر بحسب الفهرس.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**Returns:**
[IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata) - كائن [IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


تحديد ما إذا كان الكائن المحدد مساويًا للكائن الحالي.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | الكائن للمقارنة مع الكائن الحالي. |

**Returns:**
boolean - true إذا كان الكائن المحدد مساويًا للكائن الحالي؛ وإلا false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة لنوع محدد، مناسبة للاستخدام في خوارزميات التجزئة والهياكل البيانات مثل جدول التجزئة.

**Returns:**
int - رمز تجزئة للكائن الحالي.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iterator()
```


إرجاع تعداد (enumerator) يتنقل عبر المجموعة.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - IGenericEnumerator يمكن استخدامه للتنقل عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectEffectiveData> iteratorJava()
```


إرجاع مكرر جافا (java iterator) للمجموعة بأكملها.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectEffectiveData> - java.util.Iterator للمجموعة بأكملها.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة للتعبئة. |
| index | int | موضع البدء في مصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


إرجاع قيمة تُشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمنًا للخيوط). قيمة منطقية للقراءة فقط.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


إرجاع جذر التزامن. كائن للقراءة فقط.

**Returns:**
java.lang.Object