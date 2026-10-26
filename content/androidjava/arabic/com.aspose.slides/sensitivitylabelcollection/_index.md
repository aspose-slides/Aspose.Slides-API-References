---
title: SensitivityLabelCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من تسميات الحساسية المطبقة على المستند.
type: docs
url: /ar/com.aspose.slides/sensitivitylabelcollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

يمثل مجموعة من تسميات الحساسية المطبقة على المستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد تسمية الحساسية حسب الفهرس. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | يضيف تسمية الحساسية إلى نهاية المجموعة. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | يضيف SensitivityLabel إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تسمية الحساسية عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [iterator()](#iterator--) | يعيد عدادًا يجتاز المجموعة. |
| [getCount()](#getCount--) | يعيد عدد العناصر في المجموعة. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

يعيد تسمية الحساسية حسب الفهرس.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

يضيف تسمية الحساسية إلى نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| id | java.lang.String | معرف تسمية الحساسية. |
| siteId | java.util.UUID | معرف موقع Azure Active Directory (Azure AD). |
| isEnabled | boolean | علامة تشير إلى ما إذا كانت تسمية الحساسية مفعلة. |
| methodType | int | طريقة تعيين تسمية الحساسية. |

**القيمة المرجعة:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

يضيف SensitivityLabel إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | كائن SensitivityLabel الذي سيُضاف إلى نهاية المجموعة. |

**القيمة المرجعة:**
int - الفهرس الذي تم إضافة SensitivityLabel عنده.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل تسمية الحساسية عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس تسمية الحساسية التي يجب حذفها. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

يعيد عدادًا يجتاز المجموعة.

**القيمة المرجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - كائن يمكن استخدامه لتجوال عبر المجموعة.
### getCount() {#getCount--}
```
public final int getCount()
```

يعيد عدد العناصر في المجموعة. قراءة فقط  int .

**القيمة المرجعة:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |