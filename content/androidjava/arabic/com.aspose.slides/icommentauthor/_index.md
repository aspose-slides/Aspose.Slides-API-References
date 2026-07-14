---
title: ICommentAuthor
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an author of comments.
type: docs
url: /ar/com.aspose.slides/icommentauthor/
---```
public interface ICommentAuthor
```

يمثل مؤلفًا للتعليقات.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getName()](#getName--) | إرجاع أو تعيين اسم المؤلف. |
| [setName(String value)](#setName-java.lang.String-) | إرجاع أو تعيين اسم المؤلف. |
| [getInitials()](#getInitials--) | إرجاع أو تعيين الأحرف الأولى للمؤلف. |
| [setInitials(String value)](#setInitials-java.lang.String-) | إرجاع أو تعيين الأحرف الأولى للمؤلف. |
| [getComments()](#getComments--) | إرجاع مجموعة التعليقات التي أنشأها هذا المؤلف. |
| [remove()](#remove--) | إزالة المؤلف من المجموعة الأصلية. |
### getName() {#getName--}
```
public abstract String getName()
```

إرجاع أو تعيين اسم المؤلف. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

إرجاع أو تعيين اسم المؤلف. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getInitials() {#getInitials--}
```
public abstract String getInitials()
```

إرجاع أو تعيين الأحرف الأولى للمؤلف. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setInitials(String value) {#setInitials-java.lang.String-}
```
public abstract void setInitials(String value)
```

إرجاع أو تعيين الأحرف الأولى للمؤلف. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getComments() {#getComments--}
```
public abstract ICommentCollection getComments()
```

إرجاع مجموعة التعليقات التي أنشأها هذا المؤلف. قراءة فقط [ICommentCollection](../../com.aspose.slides/icommentcollection).

**الإرجاع:**
[ICommentCollection](../../com.aspose.slides/icommentcollection)
### remove() {#remove--}
```
public abstract void remove()
```

يزيل المؤلف من المجموعة الأصلية.