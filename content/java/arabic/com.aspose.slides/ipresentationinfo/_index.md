---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Information about presentation file
type: docs
url: /ar/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

معلومات حول ملف العرض
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | يحصل على True إذا كان العرض المرتبط مُشفّرًا، وإلا False. |
| [isPasswordProtected()](#isPasswordProtected--) | يحصل على قيمة تشير إلى ما إذا كان العرض المرتبط محميًا بكلمة مرور للفتح. |
| [isWriteProtected()](#isWriteProtected--) | يحصل على قيمة تشير إلى ما إذا كان العرض المرتبط محميًا من الكتابة. |
| [getLoadFormat()](#getLoadFormat--) | يحصل على تنسيق العرض المرتبط. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور للفتح. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي من الكتابة. |
| [readDocumentProperties()](#readDocumentProperties--) | يحصل على خصائص المستند للعرض المرتبط. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | يقوم بتحديث خصائص العرض المرتبط. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | يكتب العرض المرتبط إلى تدفق. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | يكتب العرض المرتبط إلى ملف. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


يحصل على True إذا كان العرض المرتبط مُشفّرًا، وإلا False. قيمة منطقية للقراءة فقط boolean.

**الإرجاع:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


يحصل على قيمة تشير إلى ما إذا كان العرض المرتبط محميًا بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**الإرجاع:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


يحصل على قيمة تشير إلى ما إذا كان العرض المرتبط محميًا من الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

إذا كان العرض محميًا بكلمة مرور للفتح، تكون قيمة الخاصية مساوية لـ NotDefined. انظر تعداد [NullableBool](../../com.aspose.slides/nullablebool).

**الإرجاع:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


يحصل على تنسيق العرض المرتبط. للقراءة فقط [LoadFormat](../../com.aspose.slides/loadformat).

**الإرجاع:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور التي سيتم التحقق منها. |

--------------------

عند كون كلمة المرور null أو فارغة، تُرجع هذه الطريقة false. |

**الإرجاع:**
boolean - True إذا كان العرض محميًا بكلمة مرور للفتح وكانت كلمة المرور صحيحة وإلا false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي من الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور التي سيتم التحقق منها. |

--------------------

1. يجب عليك التحقق من الخاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الطريقة. 2. عند كون كلمة المرور null أو فارغة، تُرجع هذه الطريقة false. |

**الإرجاع:**
boolean - True إذا كان العرض محميًا من الكتابة وكانت كلمة المرور صحيحة. False وإلا.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


يحصل على خصائص المستند للعرض المرتبط.

**الإرجاع:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - خصائص المستند [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


يقوم بتحديث خصائص العرض المرتبط.

--------------------

> ```
> هذه العينة توضح كيفية استدعاء طريقة #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) لت
>  تحديث خصائص المستند التي تم إرجاعها بواسطة استدعاء طريقة #readDocumentProperties.readDocumentProperties.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | خصائص المستند [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


يكتب العرض المرتبط إلى تدفق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | يجب أن يكون التدفق قابلًا للبحث والكتابة. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


يكتب العرض المرتبط إلى ملف.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف العرض. |