---
title: IDigitalSignature
second_title: Aspose.Slides for Java API Reference
description: التوقيع الرقمي في الملف الموقّع.
type: docs
url: /ar/com.aspose.slides/idigitalsignature/
---```
public interface IDigitalSignature
```

التوقيع الرقمي في الملف الموقّع.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCertificate()](#getCertificate--) | كائن الشهادة الذي استخدم لتوقيع المستند. |
| [isValid()](#isValid--) | إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، ستكون هذه القيمة true. |
| [getSignTime()](#getSignTime--) | الوقت الذي تم فيه توقيع المستند. |
| [getComments()](#getComments--) | غرض التوقيع. |
| [setComments(String value)](#setComments-java.lang.String-) | غرض التوقيع. |
### getCertificate() {#getCertificate--}
```
public abstract byte[] getCertificate()
```

كائن الشهادة الذي استخدم لتوقيع المستند. للقراءة فقط byte[].

**القيمة المرجعة:**  
byte[]
### isValid() {#isValid--}
```
public abstract boolean isValid()
```

إذا كان هذا التوقيع الرقمي صالحًا ولم يتم العبث بالمستند، ستكون هذه القيمة true. للقراءة فقط boolean.

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

الوقت الذي تم فيه توقيع المستند. للقراءة فقط java.util.Date.

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

غرض التوقيع. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

غرض التوقيع. قراءة/كتابة String.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |