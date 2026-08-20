---
title: IPortionFormat
second_title: مرجع API ل Aspose.Slides للـ Java
description: تحتوي هذه الفئة على خصائص تنسيق جزء النص.
type: docs
url: /ar/com.aspose.slides/iportionformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

هذه الفئة تحتوي على خصائص تنسيق جزء النص. على عكس [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)، جميع خصائص هذه الفئة قابلة للكتابة.

--------------------

تُستخدم هذه الفئة لإرجاع ومعالجة خصائص تنسيق جزء النص المحدد. وهذا يعني أن الوراثة لا تُطبق عند الحصول على القيم، لذلك في معظم الحالات ستحصل على قيم تعني "غير معرف".

للحصول على قيم تنسيق المعاملات الفعّالة بما في ذلك الموروثة، تحتاج إلى استخدام طريقة [getEffective](../../com.aspose.slides/iportionformat\#getEffective) التي تُرجع كائنًا من نوع [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | يرجع أو يضبط معرف العلامة المرجعية. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | يرجع أو يضبط معرف العلامة المرجعية. |
| [getSmartTagClean()](#getSmartTagClean--) | يحدد ما إذا كان يجب تنظيف العلامة الذكية. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | يحدد ما إذا كان يجب تنظيف العلامة الذكية. |
| [getEffective()](#getEffective--) | يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

يرجع أو يضبط معرف العلامة المرجعية. قابل للقراءة/الكتابة String.

**الإرجاع:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

يرجع أو يضبط معرف العلامة المرجعية. قابل للقراءة/الكتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

يحدد ما إذا كان يجب تنظيف العلامة الذكية. لم يتم تطبيق الوراثة. قابل للقراءة/الكتابة boolean.

**الإرجاع:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

يحدد ما إذا كان يجب تنظيف العلامة الذكية. لم يتم تطبيق الوراثة. قابل للقراءة/الكتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

يحصل على بيانات تنسيق الجزء الفعّالة مع تطبيق الوراثة.

**الإرجاع:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).