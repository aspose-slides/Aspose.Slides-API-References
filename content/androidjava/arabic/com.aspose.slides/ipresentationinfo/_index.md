---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
url: /ar/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

معلومات حول ملف العرض التقديمي
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | يُعيد True إذا كان العرض المربوط مشفراً، وإلا False. |
| [isPasswordProtected()](#isPasswordProtected--) | يُعيد قيمة تشير إلى ما إذا كان العرض المربوط محمياً بكلمة مرور للفتح. |
| [isWriteProtected()](#isWriteProtected--) | يُعيد قيمة تشير إلى ما إذا كان العرض المربوط محمياً من الكتابة. |
| [getLoadFormat()](#getLoadFormat--) | يُعيد تنسيق العرض المربوط. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمى بكلمة مرور للفتح. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمى من الكتابة. |
| [readDocumentProperties()](#readDocumentProperties--) | يحصل على خصائص المستند للعرض المربوط. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | يقوم بتحديث خصائص العرض المربوط. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | يكتب العرض المربوط إلى التدفق. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | يكتب العرض المربوط إلى الملف. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


يُعيد True إذا كان العرض المربوط مشفراً، وإلا False. قيمة منطقية لــRead-only.

**القيمة المرجعة:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


يُعيد قيمة تشير إلى ما إذا كان العرض المربوط محمياً بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**القيمة المرجعة:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


يُعيد قيمة تشير إلى ما إذا كان العرض المربوط محمياً من الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

إذا كان العرض محمياً بكلمة مرور للفتح، تكون قيمة الخاصية مساوية لـ NotDefined. راجع تعداد [NullableBool](../../com.aspose.slides/nullablebool).

**القيمة المرجعة:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


يُعيد تنسيق العرض المربوط. قيمة لــRead-only [LoadFormat](../../com.aspose.slides/loadformat).

**القيمة المرجعة:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمى بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق. |

--------------------

عند كون كلمة المرور null أو فارغة، تُعيد هذه الدالة false.

**القيمة المرجعة:**
boolean - True إذا كان العرض محمياً بكلمة مرور للفتح وكانت كلمة المرور صحيحة وfalse غير ذلك.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمى من الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق. |

--------------------

1. يجب عليك التحقق من الخاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الدالة. 2. عندما تكون كلمة المرور null أو فارغة، تُعيد هذه الدالة false.

**القيمة المرجعة:**
boolean - True إذا كان العرض محمياً من الكتابة وكانت كلمة المرور صحيحة. False غير ذلك.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


يحصل على خصائص المستند للعرض المربوط.

**القيمة المرجعة:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - خصائص المستند [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


يقوم بتحديث خصائص العرض المربوط.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | خصائص المستند [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


يكتب العرض المربوط إلى التدفق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | يجب أن يكون التدفق قابلًا للسعي والكتابة. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


يكتب العرض المربوط إلى الملف.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| file | java.lang.String | ملف العرض. |