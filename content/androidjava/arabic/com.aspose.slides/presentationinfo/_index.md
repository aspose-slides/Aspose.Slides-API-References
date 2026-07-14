---
title: PresentationInfo
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: معلومات حول ملف العرض التقديمي
type: docs
url: /ar/com.aspose.slides/presentationinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

معلومات حول ملف العرض التقديمي
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | يعيد True إذا كان العرض المرتبط مشفرًا، وإلا False. |
| [isPasswordProtected()](#isPasswordProtected--) | يعيد قيمة تُظهر ما إذا كان العرض المرتبط محميًا بكلمة مرور للفتح. |
| [isWriteProtected()](#isWriteProtected--) | يعيد قيمة تُظهر ما إذا كان العرض المرتبط محميًا ضد الكتابة. |
| [getLoadFormat()](#getLoadFormat--) | يعيد تنسيق العرض المرتبط. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور للفتح. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي ضد الكتابة. |
| [readDocumentProperties()](#readDocumentProperties--) | يعيد خصائص المستند للعرض المرتبط. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | يحدّث خصائص العرض المرتبط. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | يكتب العرض المرتبط إلى تدفق. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | يكتب العرض المرتبط إلى ملف. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

يعيد True إذا كان العرض المرتبط مشفرًا، وإلا False. boolean للقراءة فقط.

**الإرجاع:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

يعيد قيمة تُظهر ما إذا كان العرض المرتبط محميًا بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**الإرجاع:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

يعيد قيمة تُظهر ما إذا كان العرض المرتبط محميًا ضد الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

إذا كان العرض محميًا بكلمة مرور للفتح، تكون قيمة الخاصية مساوية لـ NotDefined.

**الإرجاع:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

يعيد تنسيق العرض المرتبط. للقراءة فقط [LoadFormat](../../com.aspose.slides/loadformat).

**الإرجاع:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور للفتح.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق منها. |

--------------------

عندما تكون كلمة المرور null أو فارغة، تُرجِع هذه الطريقة false. |

**الإرجاع:**
boolean - True إذا كان العرض محميًا بكلمة مرور للفتح وكانت كلمة المرور صحيحة وإلا False.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي ضد الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق منها. |

--------------------

1. يجب عليك التحقق من الخاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الطريقة. 2. عندما تكون كلمة المرور null أو فارغة، تُرجِع هذه الطريقة false. |

**الإرجاع:**
boolean - True إذا كان العرض محميًا ضد الكتابة وكانت كلمة المرور صحيحة. False otherwise.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

يعيد خصائص المستند للعرض المرتبط.

**الإرجاع:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

يحدّث خصائص العرض المرتبط.

--------------------

> ```
> هذا المثال يوضح كيفية استدعاء طريقة #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) لت
>  تحديث خصائص المستند التي تم إرجاعها من استدعاء طريقة #readDocumentProperties.readDocumentProperties.
>  
>  IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

يكتب العرض المرتبط إلى تدفق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | يجب أن يكون التدفق قابلًا للبحث والكتابة. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

يكتب العرض المرتبط إلى ملف.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف العرض التقديمي. |