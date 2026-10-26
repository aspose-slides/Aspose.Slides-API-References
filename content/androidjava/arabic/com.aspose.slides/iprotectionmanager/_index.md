---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: إدارة حماية كلمة مرور العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

إدارة حماية كلمة مرور العرض التقديمي.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | هذه الخاصية ذات معنى إذا كان العرض محمياً بكلمة مرور. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | هذه الخاصية ذات معنى إذا كان العرض محمياً بكلمة مرور. |
| [isEncrypted()](#isEncrypted--) | يحصل على قيمة تشير إلى ما إذا كانت هذه النسخة مشفرة. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | هذه الخاصية ذات معنى إذا كان ملف العرض محمياً بكلمة مرور وكانت خصائص المستند لهذا الملف عامة. |
| [isWriteProtected()](#isWriteProtected--) | يحصل على قيمة تشير إلى ما إذا كان هذا العرض محميًا من الكتابة. |
| [getEncryptionPassword()](#getEncryptionPassword--) | يرجع كلمة مرور التشفير. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | يحصل أو يحدد توصية القراءة فقط. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | يحصل أو يحدد توصية القراءة فقط. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | يشفر العرض التقديمي باستخدام كلمة المرور المحددة. |
| [removeEncryption()](#removeEncryption--) | يزيل التشفير. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | تعيين حماية الكتابة لهذا العرض باستخدام كلمة المرور المحددة. |
| [removeWriteProtection()](#removeWriteProtection--) | يزيل حماية الكتابة لهذا العرض. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | يحدد ما إذا كان العرض محمياً بكلمة مرور للتعديل. |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

هذه الخاصية ذات معنى إذا كان العرض محمياً بكلمة مرور. إذا كانت true فإن خصائص المستند مشفرة في ملف العرض. إذا كانت false فإن خصائص المستند عامة بينما العرض مشفر. قابل للقراءة والكتابة من نوع boolean.

**الإرجاع:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

هذه الخاصية ذات معنى إذا كان العرض محمياً بكلمة مرور. إذا كانت true فإن خصائص المستند مشفرة في ملف العرض. إذا كانت false فإن خصائص المستند عامة بينما العرض مشفر. قابل للقراءة والكتابة من نوع boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

يحصل على قيمة تشير إلى ما إذا كانت هذه النسخة مشفرة. للقراءة فقط من نوع boolean.

القيمة: true إذا تم تحميل العرض من ملف مشفر أو تم استدعاء طريقة \#encrypt(String).encrypt(String)؛ وإلا false.

**الإرجاع:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

هذه الخاصية ذات معنى إذا كان ملف العرض محمياً بكلمة مرور وكانت خصائص المستند لهذا الملف عامة. القيمة true تعني أنه تم تحميل خصائص المستند فقط من ملف عرض مشفر دون استخدام كلمة مرور. القيمة false تعني أنه تم تحميل العرض المشفر بالكامل باستخدام كلمة المرور الصحيحة، وليس فقط خصائص المستند. إذا لم يكن العرض مشفراً تكون قيمة الخاصية دائمًا false. إذا لم تكن خصائص المستند لملف مشفر عامة تكون قيمة الخاصية دائمًا false. إذا كان PresentationEx.EncryptDocumentProperties true فإن قيمة الخاصية IsOnlyDocumentPropertiesLoaded تكون دائمًا false. للقراءة فقط من نوع boolean.

**الإرجاع:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

يحصل على قيمة تشير إلى ما إذا كان هذا العرض محميًا من الكتابة. للقراءة فقط من نوع boolean.

**الإرجاع:**
boolean

### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

يرجع كلمة مرور التشفير. للقراءة فقط من نوع String.

**الإرجاع:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

يحصل أو يحدد توصية القراءة فقط. قابل للقراءة والكتابة من نوع boolean.

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

يحصل أو يحدد توصية القراءة فقط. قابل للقراءة والكتابة من نوع boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

يشفر العرض التقديمي باستخدام كلمة المرور المحددة.

**المعاملات:**
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

تعيين حماية الكتابة لهذا العرض باستخدام كلمة المرور المحددة.

**المعاملات:**
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

يحدد ما إذا كان العرض محمياً بكلمة مرور للتعديل.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| password | java.lang.String | كلمة المرور للتحقق.

--------------------

1. يجب عليك التحقق من الخاصية (\#isWriteProtected.isWriteProtected) قبل استدعاء هذه الطريقة. 2. عندما تكون كلمة المرور فارغة أو null، تُرجع هذه الطريقة false. |
**الإرجاع:**
boolean - True إذا كانت كلمة المرور صالحة؛ وإلا false.