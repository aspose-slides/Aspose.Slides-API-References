---
title: PresentationInfo
second_title: مرجع API لـ Aspose.Slides للـ Java
description: معلومات عن ملف العرض التقديمي
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

معلومات عن ملف العرض التقديمي
## Methods

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | يحصل على True إذا كان العرض المربوط مشفراً، وإلا False. |
| [isPasswordProtected()](#isPasswordProtected--) | يحصل على قيمة تشير إلى ما إذا كان العرض المربوط محمياً بكلمة مرور للفتح. |
| [isWriteProtected()](#isWriteProtected--) | يحصل على قيمة تشير إلى ما إذا كان العرض المربوط محمياً من الكتابة. |
| [getLoadFormat()](#getLoadFormat--) | يحصل على تنسيق العرض المربوط. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور للفتح. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي من الكتابة. |
| [readDocumentProperties()](#readDocumentProperties--) | يحصل على خصائص المستند للعرض المربوط. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | يحدث خصائص العرض المربوط. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | يكتب العرض المربوط إلى تدفق. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | يكتب العرض المربوط إلى ملف. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

يحصل على True إذا كان العرض المربوط مشفراً، وإلا False. Read-only boolean.

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

يحصل على قيمة تشير إلى ما إذا كان العرض المربوط محمياً بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

يحصل على قيمة تشير إلى ما إذا كان العرض المربوط محمياً من الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

إذا كان العرض محمياً بكلمة مرور للفتح، تكون قيمة الخاصية مساوية لـ NotDefined.

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

يحصل على تنسيق العرض المربوط. Read-only [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

يتحقق مما إذا كانت كلمة المرور صحيحة للعرض المحمي بكلمة مرور للفتح.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق منها.

--------------------

عند كون كلمة المرور null أو فارغة، تُعيد هذه الطريقة false. |

**Returns:**
boolean - True إذا كان العرض محمياً بكلمة مرور للفتح وكانت كلمة المرور صحيحة، وfalse otherwise.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

يتحقق مما إذا كانت كلمة المرور للتعديل صحيحة للعرض المحمي من الكتابة.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق منها.

--------------------

1. يجب عليك فحص الخاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الطريقة. 2. عندما تكون كلمة المرور null أو فارغة، تُعيد هذه الطريقة false. |

**Returns:**
boolean - True إذا كان العرض محمياً من الكتابة وكانت كلمة المرور صحيحة. False otherwise.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

يحصل على خصائص المستند للعرض المربوط.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

يُحدث خصائص العرض المربوط.

--------------------

> ```
> هذا المثال يوضح كيفية استدعاء #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) الطريقة لت
>  تحديث خصائص المستند التي تم إرجاعها بواسطة استدعاء #readDocumentProperties.readDocumentProperties الطريقة.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

يكتب العرض المربوط إلى تدفق.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | يجب أن يكون التدفق قابلًا للSeek والكتابة. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

يكتب العرض المربوط إلى ملف.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | ملف العرض التقديمي. |