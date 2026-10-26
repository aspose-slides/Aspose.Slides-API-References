---
title: ICustomXmlPartCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من أجزاء XML المخصصة.
type: docs
url: /ar/com.aspose.slides/icustomxmlpartcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ICustomXmlPartCollection extends IGenericCollection<ICustomXmlPart>
```

يمثل مجموعة من أجزاء XML المخصصة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the element at the specified index. |
| [add(byte[] xmlData)](#add-byte---) | يضيف جزء XML مخصص جديد. |
| [add(String xmlString)](#add-java.lang.String-) | يضيف جزء XML مخصص جديد. |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | يضيف جزء XML مخصص جديد. |
| [removeAt(int index)](#removeAt-int-) | يزيل جزء XML مخصص في الفهرس المحدد. |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | يزيل أول حدوث لعنصر محدد من المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICustomXmlPart get_Item(int index)
```

يُعيد العنصر في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد الحصول عليه. |

**القيمة المرجعة:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - العنصر في الفهرس المحدد.
### add(byte[] xmlData) {#add-byte---}
```
public abstract ICustomXmlPart add(byte[] xmlData)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| xmlData | byte[] | بيانات XML للجزء الجديد الذي سيُضاف. |

**القيمة المرجعة:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.
### add(String xmlString) {#add-java.lang.String-}
```
public abstract ICustomXmlPart add(String xmlString)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| xmlString | java.lang.String | سلسلة XML للجزء الجديد الذي سيُضاف. |

**القيمة المرجعة:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public abstract ICustomXmlPart add(InputStream inputStream)
```

يضيف جزء XML مخصص جديد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| inputStream | java.io.InputStream | تدفق الإدخال الذي يحتوي على بيانات XML للجزء الجديد الذي سيُضاف. |

**القيمة المرجعة:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - جزء XML مخصص تم إنشاؤه.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل جزء XML مخصص في الفهرس المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public abstract boolean remove(ICustomXmlPart item)
```

يزيل أول حدوث لعنصر محدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | جزء XML المخصص الذي سيُزال. |

**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح؛ وإلا false.
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.