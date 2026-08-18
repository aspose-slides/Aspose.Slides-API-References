---
title: CellCircularReferenceException
second_title: Aspose.Slides Java API Referansı
description: Formülün kendi hücresine doğrudan veya dolaylı olarak referans verdiği bir veya daha fazla döngüsel referans tespit edildiğinde fırlatılan istisna.
type: docs
url: /tr/com.aspose.slides/cellcircularreferenceexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Bir formülün kendi hücresine doğrudan veya dolaylı olarak referans vermesi durumunda bir veya daha fazla döngüsel referans tespit edildiğinde fırlatılan istisna.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini başlatır. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini belirtilen hata mesajı ile başlatır. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve bu hatanın nedeni olan iç istisna referansı ile başlatır. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve döngüsel hücre referansı ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getReference()](#getReference--) | Döngüsel bir hücre referansı alır. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini başlatır.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini belirtilen hata mesajı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata mesajını açıklayan bir dize. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve bu hatanın nedeni olan iç istisna referansı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata mesajını açıklayan bir dize. |
| innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve döngüsel hücre referansı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata mesajını açıklayan bir dize. |
| reference | java.lang.String | Döngüsel bir hücre referansı. |

### getReference() {#getReference--}
```
public final String getReference()
```

Döngüsel bir hücre referansı alır.

**Döndürür:**
java.lang.String