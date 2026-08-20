---
title: SensitivityLabelCollection
second_title: مرجع API Aspose.Slides للجاوا
description: يمثل مجموعة من تسميات الحساسية المطبقة على المستند.
type: docs
url: /ar/com.aspose.slides/sensitivitylabelcollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المُطبقة:**
[com.aspose.slides.ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
```
public final class SensitivityLabelCollection extends DomObject<Presentation> implements ISensitivityLabelCollection
```

يمثل مجموعة من تسميات الحساسية المطبقة على المستند.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع تسمية الحساسية وفق الفهرس. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | يضيف تسمية الحساسية في نهاية المجموعة. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | يضيف SensitivityLabel إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تسمية الحساسية عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [iterator()](#iterator--) | يرجع عدّادًا يقوم بالتنقل عبر المجموعة. |
| [getCount()](#getCount--) | يرجع عدد العناصر في المجموعة. |
| [copyTo(ISensitivityLabel[] array, int index)](#copyTo-com.aspose.slides.ISensitivityLabel---int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
### get_Item(int index) {#get-Item-int-}
```
public final ISensitivityLabel get_Item(int index)
```

يرجع تسمية الحساسية حسب الفهرس.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public final ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

يضيف تسمية الحساسية في نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| id | java.lang.String | معرف تسمية الحساسية. |
| siteId | java.util.UUID | معرف موقع Azure Active Directory (Azure AD). |
| isEnabled | boolean | إشارة تشير إلى ما إذا كانت تسمية الحساسية مفعلة. |
| methodType | int | طريقة تعيين تسمية الحساسية. |

**القيمة المرتجعة:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)
### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public final int add(ISensitivityLabel label)
```

يضيف SensitivityLabel إلى المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | كائن SensitivityLabel الذي سيُضاف إلى نهاية المجموعة. |

**القيمة المرتجعة:**
int - الفهرس الذي تمت إضافة SensitivityLabel إليه.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل تسمية الحساسية عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الخاص بتسمية الحساسية التي يجب حذفها. |

### clear() {#clear--}
```
public final void clear()
```

يزيل جميع العناصر من المجموعة.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISensitivityLabel> iterator()
```

يرجع عدّادًا يقوم بالتنقل عبر المجموعة.

**القيمة المرتجعة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISensitivityLabel> - مُعدِّد يمكن استخدامه للتنقل عبر المجموعة.
### getCount() {#getCount--}
```
public final int getCount()
```

يرجع عدد العناصر في المجموعة. قراءة فقط  int .

**القيمة المرتجعة:**
int
### copyTo(ISensitivityLabel[] array, int index) {#copyTo-com.aspose.slides.ISensitivityLabel---int-}
```
public final void copyTo(ISensitivityLabel[] array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [ISensitivityLabel\[\]](../../com.aspose.slides/isensitivitylabel) | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |