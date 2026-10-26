---
title: ICommentAuthorCollection
second_title: مرجع API لـ Aspose.Slides لل Java
description: يمثل مجموعة من مؤلفي التعليقات.
type: docs
url: /ar/com.aspose.slides/icommentauthorcollection/
---
**جميع الواجهات المطبقة:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

يمثل مجموعة من مؤلفي التعليقات.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | إضافة مؤلف جديد في نهاية مجموعة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين. |
| [findByName(String name)](#findByName-java.lang.String-) | العثور على مؤلف في مجموعة حسب الاسم. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | العثور على مؤلف في مجموعة حسب الاسم والأحرف الأولى. |
| [removeAt(int index)](#removeAt-int-) | يزيل المؤلف في الفهرس المحدد من المجموعة. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | يزيل أول ظهور للمؤلف المحدد في مجموعة. |
| [clear()](#clear--) | يزيل جميع المؤلفين من مجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقـراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعية:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

إضافة مؤلف جديد في نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم مؤلف جديد. |
| initials | java.lang.String | الأحرف الأولى لمؤلف جديد. |

**القيمة المرجعية:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - كائن جديد [ICommentAuthor](../../com.aspose.slides/icommentauthor).
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين.

**القيمة المرجعية:**
com.aspose.slides.ICommentAuthor[] - مصفوفة من [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

العثور على مؤلف في مجموعة حسب الاسم.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف للبحث عنه. |

**القيمة المرجعية:**
com.aspose.slides.ICommentAuthor[] - مؤلف أو فارغ.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

العثور على مؤلف في مجموعة حسب الاسم والأحرف الأولى.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف للبحث عنه. |
| initials | java.lang.String | الأحرف الأولى للمؤلف للبحث عنه. |

**القيمة المرجعية:**
com.aspose.slides.ICommentAuthor[] - مؤلف أو فارغ.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل المؤلف في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر المراد إزالته. |
### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

يزيل أول ظهور للمؤلف المحدد في مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | المؤلف لإزالته من مجموعة. |
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع المؤلفين من مجموعة.