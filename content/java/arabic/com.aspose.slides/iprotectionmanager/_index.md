---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: إدارة حماية كلمة مرور العرض.
type: docs
url: /ar/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

إدارة حماية كلمة مرور العرض.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. |
| [isEncrypted()](#isEncrypted--) | يحصل على قيمة تشير ما إذا كانت هذه المثيلة مشفّرة. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور وخصائص المستند لهذا الملف عامة. |
| [isWriteProtected()](#isWriteProtected--) | يحصل على قيمة تشير ما إذا كان هذا العرض محميًا ضد الكتابة. |
| [getEncryptionPassword()](#getEncryptionPassword--) | يعيد كلمة مرور التشفير. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | يحصل أو يضع توصية للقراءة فقط. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | يحصل أو يضع توصية للقراءة فقط. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | يشفر العرض باستخدام كلمة مرور محددة. |
| [removeEncryption()](#removeEncryption--) | يزيل التشفير. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | يحدد حماية كتابة لهذا العرض باستخدام كلمة مرور محددة. |
| [removeWriteProtection()](#removeWriteProtection--) | يزيل حماية الكتابة لهذا العرض. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يحدد ما إذا كان العرض محميًا بكلمة مرور للتعديل. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. إذا كان true فإن خصائص المستند مشفّرة في ملف العرض. إذا كان false فإن خصائص المستند عامة بينما يكون العرض مشفّراً. منطقي قابل للقراءة والكتابة.

**الإرجاع:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. إذا كان true فإن خصائص المستند مشفّرة في ملف العرض. إذا كان false فإن خصائص المستند عامة بينما يكون العرض مشفّراً. منطقي قابل للقراءة والكتابة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

يحصل على قيمة تشير ما إذا كانت هذه المثيلة مشفّرة. منطقي للقراءة فقط.

القيمة: true إذا تم تحميل العرض من ملف مشفّر أو تم استدعاء طريقة \#encrypt(String).encrypt(String)؛ وإلا false.

**الإرجاع:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور وخصائص المستند لهذا الملف عامة. القيمة true تعني أنه تم تحميل خصائص المستند فقط من ملف عرض مشفّر دون استخدام كلمة مرور. القيمة false تعني أن العرض المشفّر بالكامل تم تحميله باستخدام كلمة المرور الصحيحة، وليس فقط خصائص المستند. إذا لم يكن العرض مشفّرًا فإن الخاصية دائمًا false. إذا لم تكن خصائص المستند لملف مشفّر عامة فإن الخاصية دائمًا false. إذا كان PresentationEx.EncryptDocumentProperties true فإن قيمة IsOnlyDocumentPropertiesLoaded دائمًا false. منطقي للقراءة فقط.

**الإرجاع:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

يحصل على قيمة تشير ما إذا كان هذا العرض محميًا ضد الكتابة. منطقي للقراءة فقط.

**الإرجاع:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

يعيد كلمة مرور التشفير. سلسلة للقراءة فقط.

**الإرجاع:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

يحصل أو يضع توصية للقراءة فقط. منطقي قابل للقراءة والكتابة.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**الإرجاع:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

يحصل أو يضع توصية للقراءة فقط. منطقي قابل للقراءة والكتابة.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

يشفر العرض باستخدام كلمة مرور محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| encryptionPassword | java.lang.String | كلمة المرور. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

يزيل التشفير.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

يحدد حماية كتابة لهذا العرض باستخدام كلمة مرور محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

يزيل حماية الكتابة لهذا العرض.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

يحدد ما إذا كان العرض محميًا بكلمة مرور للتعديل.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للفحص. |
1. يجب عليك التحقق من الخاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الطريقة. 2. عندما تكون كلمة المرور null أو فارغة، تُرجع هذه الطريقة false. |

**الإرجاع:**
boolean - true إذا كانت كلمة المرور صالحة؛ وإلا false.