---
title: ProtectionManager
second_title: Aspose.Slides لأجهزة Android عبر مرجع API لجافا
description: إدارة حماية كلمة مرور العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/protectionmanager/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

إدارة حماية كلمة مرور العرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | هذه الخاصية ذات معنى إذا كان العرض محميًا بكلمة مرور. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | هذه الخاصية ذات معنى إذا كان العرض محميًا بكلمة مرور. |
| [isEncrypted()](#isEncrypted--) | يحصل على قيمة تُشير إلى ما إذا كان هذا الكائن مشفرًا. قيمة منطقية للقراءة فقط. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور وخصائص المستند لهذا الملف عامة. |
| [isWriteProtected()](#isWriteProtected--) | يحصل على قيمة تُشير إلى ما إذا كان هذا العرض محميًا ضد الكتابة. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | يشفر العرض باستخدام كلمة المرور المحددة. |
| [removeEncryption()](#removeEncryption--) | يزيل التشفير. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | يحدد حماية الكتابة لهذا العرض باستخدام كلمة مرور محددة. |
| [removeWriteProtection()](#removeWriteProtection--) | يزيل حماية الكتابة لهذا العرض. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يحدد ما إذا كان العرض محميًا بكلمة مرور للتعديل. |
| [getEncryptionPassword()](#getEncryptionPassword--) | يحصل على كلمة المرور المستخدمة لتشفير العرض. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | يحصل أو يضبط توصية القراءة فقط. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | يحصل أو يضبط توصية القراءة فقط. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

هذه الخاصية ذات معنى إذا كان العرض محميًا بكلمة مرور. إذا كانت true فإن خصائص المستند مشفرة في ملف العرض. إذا كانت false فإن خصائص المستند عامة بينما يكون العرض مشفرًا. قيمة منطقية للقراءة والكتابة.

**الإرجاع:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

هذه الخاصية ذات معنى إذا كان العرض محميًا بكلمة مرور. إذا كانت true فإن خصائص المستند مشفرة في ملف العرض. إذا كانت false فإن خصائص المستند عامة بينما يكون العرض مشفرًا. قيمة منطقية للقراءة والكتابة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

يحصل على قيمة تُشير إلى ما إذا كان هذا الكائن مشفرًا. قيمة منطقية للقراءة فقط.

القيمة: true إذا تم تحميل العرض من ملف مشفر أو تم استدعاء طريقة \#encrypt(String).encrypt(String)؛ وإلا false.

**الإرجاع:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

هذه الخاصية ذات معنى إذا كان ملف العرض محميًا بكلمة مرور وخصائص المستند لهذا الملف عامة. قيمة true تعني أن خصائص المستند فقط تم تحميلها من ملف عرض مشفر دون استخدام كلمة مرور. قيمة false تعني أن العرض المشفر بالكامل تم تحميله باستخدام كلمة المرور الصحيحة، وليس فقط خصائص المستند. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تكون دائمًا false. إذا لم تكن خصائص المستند لملف مشفر عامة فإن قيمة الخاصية تكون دائمًا false. إذا كان Presentation.EncryptDocumentProperties هو true فإن قيمة IsOnlyDocumentPropertiesLoaded تكون دائمًا false. قيمة منطقية للقراءة فقط.

**الإرجاع:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

يحصل على قيمة تُشير إلى ما إذا كان هذا العرض محميًا ضد الكتابة. قيمة منطقية للقراءة فقط.

**الإرجاع:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

يشفر العرض باستخدام كلمة المرور المحددة.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| encryptionPassword | java.lang.String | كلمة المرور. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

يزيل التشفير.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

يحدد حماية الكتابة لهذا العرض باستخدام كلمة مرور محددة.

--------------------

> ```
> الكود النموذجي التالي يوضح لك كيفية تعيين حماية كتابة للعرض التقديمي.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

يزيل حماية الكتابة لهذا العرض.

--------------------

> ```
> يوضح لك هذا الكود النموذجي كيفية إزالة حماية الكتابة من عرض PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
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
| password | java.lang.String | كلمة المرور للتحقق. |

1. يجب عليك التحقق من خاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الطريقة. 2. عندما تكون كلمة المرور null أو خالية، تُرجع هذه الطريقة false. |

**الإرجاع:**
boolean - True إذا كانت كلمة المرور صالحة؛ وإلا false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

يحصل على كلمة المرور المستخدمة لتشفير العرض. قيمة منطقية للقراءة فقط.

**الإرجاع:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

يحصل أو يضبط توصية القراءة فقط. قيمة منطقية للقراءة والكتابة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

يحصل أو يضبط توصية القراءة فقط. قيمة منطقية للقراءة والكتابة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |