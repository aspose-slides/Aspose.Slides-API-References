---
title: ISensitivityLabelCollection
second_title: مرجع API Aspose.Slides للـ Java
description: يمثل مجموعة من تسميات الحساسية المطبقة على المستند.
type: docs
url: /ar/com.aspose.slides/isensitivitylabelcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISensitivityLabelCollection extends System.Collections.Generic.IGenericEnumerable<ISensitivityLabel>
```

يمثل مجموعة من تسميات الحساسية المطبقة على المستند.

## الطرق

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تُرجع تسمية الحساسية بواسطة الفهرس. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | يضيف تسمية الحساسية في نهاية المجموعة. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | يضيف SensitivityLabel إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تسمية الحساسية في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع العناصر في المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

تُرجع تسمية الحساسية بواسطة الفهرس. للقراءة فقط [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

يضيف تسمية الحساسية في نهاية المجموعة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | معرف تسمية الحساسية. |
| siteId | java.util.UUID | معرف موقع Azure Active Directory (Azure AD). |
| isEnabled | boolean | علامة تُشير إلى ما إذا كانت تسمية الحساسية مفعلة. |
| methodType | int | طريقة التعيين لتسمية الحساسية. |

**الإرجاع:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

يضيف SensitivityLabel إلى المجموعة.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | كائن SensitivityLabel الذي سيُضاف في نهاية المجموعة. |

**الإرجاع:**
int - الفهرس الذي أُضيف فيه SensitivityLabel.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل تسمية الحساسية في الفهرس المحدد.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | فهرس تسمية الحساسية التي يجب حذفها. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد جميع العناصر في المجموعة. للقراءة فقط int .

**الإرجاع:**
int