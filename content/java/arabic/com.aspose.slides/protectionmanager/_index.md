---
title: ProtectionManager
second_title: مرجع API لـ Aspose.Slides للغة Java
description: إدارة حماية كلمة مرور العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/protectionmanager/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

إدارة حماية كلمة مرور العرض التقديمي.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. |
| [isEncrypted()](#isEncrypted--) | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مشفرة. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور وكانت خصائص المستند لهذا الملف عامة. |
| [isWriteProtected()](#isWriteProtected--) | يحصل على قيمة تشير إلى ما إذا كان هذا العرض محميًا من الكتابة. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | يقوم بتشفير العرض باستخدام كلمة المرور المحددة. |
| [removeEncryption()](#removeEncryption--) | يزيل التشفير. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | يحدد حماية الكتابة لهذا العرض باستخدام كلمة المرور المحددة. |
| [removeWriteProtection()](#removeWriteProtection--) | يزيل حماية الكتابة لهذا العرض. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يحدد ما إذا كان العرض محميًا بكلمة مرور لتعديله. |
| [getEncryptionPassword()](#getEncryptionPassword--) | يحصل على كلمة المرور المستخدمة لتشفير العرض. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | يحصل أو يحدد توصية القراءة فقط. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | يحصل أو يحدد توصية القراءة فقط. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. إذا كان صحيحًا فإن خصائص المستند مشفرة في ملف العرض. إذا كان خاطئًا فإن خصائص المستند عامة بينما يكون العرض مشفرًا. منطقية قراءة/كتابة.

**القيمة المرجعة:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

هذه الخاصية منطقية إذا كان العرض محميًا بكلمة مرور. إذا كان صحيحًا فإن خصائص المستند مشفرة في ملف العرض. إذا كان خاطئًا فإن خصائص المستند عامة بينما يكون العرض مشفرًا. منطقية قراءة/كتابة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة مشفرة. منطقية قراءة فقط.

القيمة: true إذا تم تحميل العرض من ملف مشفر أو استُدعي الأسلوب \#encrypt(String).encrypt(String)؛ وإلا false.

**القيمة المرجعة:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

هذه الخاصية منطقية إذا كان ملف العرض محميًا بكلمة مرور وكانت خصائص المستند لهذا الملف عامة. القيمة true تعني أنه تم تحميل خصائص المستند فقط من ملف عرض مشفر دون استخدام كلمة مرور. القيمة false تعني أنه تم تحميل العرض المشفر بالكامل باستخدام كلمة مرور صحيحة، وليس فقط خصائص المستند. إذا لم يكن العرض مشفرًا فإن قيمة الخاصية تكون دائمًا false. إذا لم تكن خصائص المستند لملف مشفر عامة فإن قيمة الخاصية تكون دائمًا false. إذا كان Presentation.EncryptDocumentProperties صحيحًا فإن قيمة IsOnlyDocumentPropertiesLoaded تكون دائمًا false. منطقية قراءة فقط.

**القيمة المرجعة:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

يحصل على قيمة تشير إلى ما إذا كان هذا العرض محميًا من الكتابة. منطقية قراءة فقط.

**القيمة المرجعة:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

يقوم بتشفير العرض باستخدام كلمة المرور المحددة.

--------------------

> ```
> يعرض الكود العيني التالي كيفية تشفير عرض تقديمي لبرنامج PowerPoint.
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

يحدد حماية الكتابة لهذا العرض باستخدام كلمة المرور المحددة.

--------------------

> ```
> يعرض الكود العيني التالي كيفية تعيين حماية كتابة لعرض تقديمي.
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
> This sample code shows you how to remove the write protection from a PowerPoint Presentation.
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

يحدد ما إذا كان العرض محميًا بكلمة مرور لتعديله.

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
| password | java.lang.String | كلمة المرور للتحقق.

--------------------

1. يجب عليك التحقق من خاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الدالة. 2. عندما تكون كلمة المرور null أو فارغة، تُرجع هذه الدالة false. |

**القيمة المرجعة:**
boolean - true إذا كانت كلمة المرور صالحة؛ وإلا false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

يحصل على كلمة المرور المستخدمة لتشفير العرض. نص قراءة فقط.

**القيمة المرجعة:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

يحصل أو يحدد توصية القراءة فقط. منطقية قراءة/كتابة.

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

**القيمة المرجعة:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

يحصل أو يحدد توصية القراءة فقط. منطقية قراءة/كتابة.

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