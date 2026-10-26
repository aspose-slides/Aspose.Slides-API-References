---
title: ISensitivityLabelCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
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

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع تسمية الحساسية حسب الفهرس. |
| [add(String id, UUID siteId, boolean isEnabled, int methodType)](#add-java.lang.String-java.util.UUID-boolean-int-) | يضيف تسمية الحساسية في نهاية المجموعة. |
| [add(ISensitivityLabel label)](#add-com.aspose.slides.ISensitivityLabel-) | يضيف SensitivityLabel إلى المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل تسمية الحساسية عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد جميع العناصر في المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISensitivityLabel get_Item(int index)
```

يرجع تسمية الحساسية حسب الفهرس. للقراءة فقط [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(String id, UUID siteId, boolean isEnabled, int methodType) {#add-java.lang.String-java.util.UUID-boolean-int-}
```
public abstract ISensitivityLabel add(String id, UUID siteId, boolean isEnabled, int methodType)
```

يضيف تسمية الحساسية في نهاية المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| id | java.lang.String | معرف تسمية الحساسية. |
| siteId | java.util.UUID | معرف موقع Azure Active Directory (Azure AD). |
| isEnabled | boolean | العلم يحدد ما إذا كانت تسمية الحساسية مفعلة. |
| methodType | int | طريقة الإسناد لتسمية الحساسية. |

**القيمة المرجعة:**
[ISensitivityLabel](../../com.aspose.slides/isensitivitylabel)

### add(ISensitivityLabel label) {#add-com.aspose.slides.ISensitivityLabel-}
```
public abstract int add(ISensitivityLabel label)
```

يضيف SensitivityLabel إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| label | [ISensitivityLabel](../../com.aspose.slides/isensitivitylabel) | كائن SensitivityLabel الذي سيُضاف إلى نهاية المجموعة. |

**القيمة المرجعة:**
int - الفهرس الذي تمت إضافة SensitivityLabel إليه.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل تسمية الحساسية عند الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
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

يحصل على عدد جميع العناصر في المجموعة. للقراءة فقط  int .

**القيمة المرجعة:**
int