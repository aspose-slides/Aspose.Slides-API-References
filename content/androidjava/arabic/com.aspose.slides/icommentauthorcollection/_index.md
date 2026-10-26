---
title: ICommentAuthorCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من مؤلفي التعليقات.
type: docs
url: /ar/com.aspose.slides/icommentauthorcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ICommentAuthorCollection extends IGenericCollection<ICommentAuthor>
```

يمثل مجموعة من مؤلفي التعليقات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [addAuthor(String name, String initials)](#addAuthor-java.lang.String-java.lang.String-) | يضيف مؤلفًا جديدًا في نهاية المجموعة. |
| [toArray()](#toArray--) | ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين. |
| [findByName(String name)](#findByName-java.lang.String-) | يبحث عن مؤلف في مجموعة حسب الاسم. |
| [findByNameAndInitials(String name, String initials)](#findByNameAndInitials-java.lang.String-java.lang.String-) | يبحث عن مؤلف في مجموعة حسب الاسم والأحرف الأولى. |
| [removeAt(int index)](#removeAt-int-) | يزيل المؤلف في الفهرس المحدد من المجموعة. |
| [remove(ICommentAuthor author)](#remove-com.aspose.slides.ICommentAuthor-) | يزيل أول ظهور للمؤلف المحدد في مجموعة. |
| [clear()](#clear--) | يزيل جميع المؤلفين من مجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICommentAuthor get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [ICommentAuthor](../../com.aspose.slides/icommentauthor).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor)
### addAuthor(String name, String initials) {#addAuthor-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor addAuthor(String name, String initials)
```

يضيف مؤلفًا جديدًا في نهاية مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم مؤلف جديد. |
| initials | java.lang.String | الأحرف الأولى لمؤلف جديد. |

**القيمة المرجعة:**
[ICommentAuthor](../../com.aspose.slides/icommentauthor) - كائن [ICommentAuthor](../../com.aspose.slides/icommentauthor) جديد.
### toArray() {#toArray--}
```
public abstract ICommentAuthor[] toArray()
```

ينشئ ويعيد مصفوفة تحتوي على جميع المؤلفين.

**القيمة المرجعة:**
com.aspose.slides.ICommentAuthor[] - مصفوفة من [ICommentAuthor](../../com.aspose.slides/icommentauthor)
### findByName(String name) {#findByName-java.lang.String-}
```
public abstract ICommentAuthor[] findByName(String name)
```

يبحث عن مؤلف في مجموعة حسب الاسم.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف للبحث عنه. |

**القيمة المرجعة:**
com.aspose.slides.ICommentAuthor[] - مؤلف أو لا شيء.
### findByNameAndInitials(String name, String initials) {#findByNameAndInitials-java.lang.String-java.lang.String-}
```
public abstract ICommentAuthor[] findByNameAndInitials(String name, String initials)
```

يبحث عن مؤلف في مجموعة حسب الاسم والأحرف الأولى.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| name | java.lang.String | اسم المؤلف للبحث عنه. |
| initials | java.lang.String | الأحرف الأولى للمؤلف للبحث عنها. |

**القيمة المرجعة:**
com.aspose.slides.ICommentAuthor[] - مؤلف أو لا شيء.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل المؤلف في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

### remove(ICommentAuthor author) {#remove-com.aspose.slides.ICommentAuthor-}
```
public abstract void remove(ICommentAuthor author)
```

يزيل أول ظهور للمؤلف المحدد في مجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | المؤلف لإزالته من مجموعة. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع المؤلفين من مجموعة.