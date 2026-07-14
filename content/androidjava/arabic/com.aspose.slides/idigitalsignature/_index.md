---
title: IDigitalSignature
second_title: Aspose.Slides for Android via Java API Reference
description: Digital signature in signed file.
type: docs
url: /ar/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

التوقيع الرقمي في الملف الموقع.
## الأساليب

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | كائن الشهادة الذي استخدم لتوقيع المستند. |
| [isValid()](#isValid--) | إذا كانت هذه التوقيع الرقمي صالحًا ولم يتم التلاعب بالمستند، فإن هذه القيمة ستكون صحيحة. |
| [getSignTime()](#getSignTime--) | وقت توقيع المستند. |
| [getComments()](#getComments--) | غرض التوقيع. |
| [setComments(String value)](#setComments-java.lang.String-) | غرض التوقيع. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

كائن الشهادة الذي استخدم لتوقيع المستند. byte[] للقراءة فقط.

**القيمة المرجعة:**  
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

إذا كانت هذه التوقيع الرقمي صالحًا ولم يتم التلاعب بالمستند، فإن هذه القيمة ستكون صحيحة. boolean للقراءة فقط.

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
public abstract Date getSignTime()
```

وقت توقيع المستند. java.util.Date للقراءة فقط.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      for (IDigitalSignature signature : pres.getDigitalSignatures())
>          System.out.println("Signature check: " + (signature.IsValid ? "VALID" : "INVALID") + ", Signing time: " + signature.getSignTime());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**  
java.util.Date
### getComments() {#getComments--}
```
public abstract String getComments()
```

غرض التوقيع. String للقراءة والكتابة.

**القيمة المرجعة:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

غرض التوقيع. String للقراءة والكتابة.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |