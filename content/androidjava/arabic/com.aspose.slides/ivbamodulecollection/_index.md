---
title: IVbaModuleCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من وحدات مشروع VBA.
type: docs
url: /ar/com.aspose.slides/ivbamodulecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IVbaModuleCollection extends IGenericCollection<IVbaModule>
```

يمثل مجموعة من وحدات مشروع VBA.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | يضيف وحدة فارغة جديدة إلى مشروع VBA. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | يزيل الظهور الأول لكائن محدد من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVbaModule get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public abstract IVbaModule addEmptyModule(String name)
```

يضيف وحدة فارغة جديدة إلى مشروع VBA.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم الوحدة |

**القيمة المرجعة:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - وحدة مضافة.
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public abstract void remove(IVbaModule value)
```

يزيل الظهور الأول لكائن محدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | الوحدة التي سيتم إزالتها من المجموعة. |