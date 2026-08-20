---
title: ICommentAuthor
second_title: Aspose.Slides for Java API Reference
description: يمثل مؤلف التعليقات.
type: docs
url: /ar/com.aspose.slides/icommentauthor/
---
```
public interface ICommentAuthor
```

يمثل مؤلف التعليقات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | إرجاع أو تعيين اسم المؤلف. |
| [setName(String value)](#setName-java.lang.String-) | إرجاع أو تعيين اسم المؤلف. |
| [getInitials()](#getInitials--) | إرجاع أو تعيين الأحرف الأولية للمؤلف. |
| [setInitials(String value)](#setInitials-java.lang.String-) | إرجاع أو تعيين الأحرف الأولية للمؤلف. |
| [getComments()](#getComments--) | إرجاع مجموعة التعليقات التي أنشأها هذا المؤلف. |
| [remove()](#remove--) | إزالة المؤلف من مجموعة الوالد. |
### getName() {#getName--}
```
public abstract String getName()
```

إرجاع أو تعيين اسم المؤلف. قابل للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

إرجاع أو تعيين اسم المؤلف. قابل للقراءة والكتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

إرجاع أو تعيين الأحرف الأولية للمؤلف. قابل للقراءة والكتابة String.

**الإرجاع:**  
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

إرجاع أو تعيين الأحرف الأولية للمؤلف. قابل للقراءة والكتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

إرجاع مجموعة التعليقات التي أنشأها هذا المؤلف. للقراءة فقط [ICommentCollection](../../com.aspose.slides/icommentcollection).

**الإرجاع:**  
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

إزالة المؤلف من مجموعة الوالد.