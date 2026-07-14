---
title: DigitalSignature
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: التوقيع الرقمي في الملف الموقّع.
type: docs
url: /ar/com.aspose.slides/digitalsignature/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IDigitalSignature](../../com.aspose.slides/idigitalsignature)
```
public class DigitalSignature implements IDigitalSignature
```

التوقيع الرقمي في الملف الموقّع.

--------------------

> ```
> The following example demonstrates how to add digital signature from a PFX certificate in PowerPoint Presentation.
>  
>  // تهيئة كائن Presentation instance
>  Presentation pres = new Presentation();
>  try {
>     // إنشاء كائن DigitalSignature باستخدام ملف PFX وكلمة مرور PFX
>      DigitalSignature signature = new DigitalSignature("testsignature1.pfx", "testpass1");
>      // إضافة تعليق لتوقيع رقمي جديد
>      signature.setComments("Aspose.Slides digital signing test.");
>      // إضافة التوقيع الرقمي إلى العرض التقديمي
>      pres.getDigitalSignatures().add(signature);
>      // حفظ العرض التقديمي
>      pres.save("SomePresentationSigned.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code demonstrates how to validate digital signature of PowerPoint Presentation.
>  
>  // تهيئة كائن Presentation instance
>  Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          // التحقق مما إذا كانت جميع التوقيعات الرقمية صالحة
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>              System.out.println(signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>              allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>              System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>              System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## المُنشئات

| Constructor | Description |
| --- | --- |
| [DigitalSignature(byte[] certData, String password)](#DigitalSignature-byte---java.lang.String-) | ينشئ كائن DigitalSignature جديد مع الشهادة المحددة. |
| [DigitalSignature(String filePath, String password)](#DigitalSignature-java.lang.String-java.lang.String-) | ينشئ كائن DigitalSignature جديد مع مسار ملف الشهادة المحدد وكلمة المرور. |
## الطرق

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | كائن الشهادة الذي تم استخدامه لتوقيع المستند. |
| [isValid()](#isValid--) | إذا كان هذا التوقيع الرقمي صالحًا ولم يتم التلاعب بالمستند، ستكون هذه القيمة true. |
| [getSignTime()](#getSignTime--) | الوقت الذي تم فيه توقيع المستند. |
| [getComments()](#getComments--) | غرض التوقيع. |
| [setComments(String value)](#setComments-java.lang.String-) | غرض التوقيع. |
### DigitalSignature(byte[] certData, String password) {#DigitalSignature-byte---java.lang.String-}
```
public DigitalSignature(byte[] certData, String password)
```


ينشئ كائن DigitalSignature جديد مع الشهادة المحددة.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| certData | byte[] | مصفوفة بايت تحتوي على الشهادة |
| password | java.lang.String | كلمة المرور المطلوبة للوصول إلى الشهادة. |

### DigitalSignature(String filePath, String password) {#DigitalSignature-java.lang.String-java.lang.String-}
```
public DigitalSignature(String filePath, String password)
```


ينشئ كائن DigitalSignature جديد مع مسار ملف الشهادة المحدد وكلمة المرور.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | المسار إلى الملف الذي يحتوي على الشهادة. |
| password | java.lang.String | كلمة المرور المطلوبة للوصول إلى الشهادة. |

### getCertificate() {#getCertificate--}
```
public final byte[] getCertificate()
```


كائن الشهادة الذي تم استخدامه لتوقيع المستند. للقراءة فقط byte[].

**القيمة المرجعة:**
byte[]
### isValid() {#isValid--}
```
public final boolean isValid()
```


إذا كان هذا التوقيع الرقمي صالحًا ولم يتم التلاعب بالمستند، ستكون هذه القيمة true. للقراءة فقط boolean.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean
### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


الوقت الذي تم فيه توقيع المستند. للقراءة فقط java.util.Date.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.isValid() ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
java.util.Date
### getComments() {#getComments--}
```
public final String getComments()
```


غرض التوقيع. للقراءة/الكتابة String.

**القيمة المرجعة:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


غرض التوقيع. للقراءة/الكتابة String.

**الوسائط:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |