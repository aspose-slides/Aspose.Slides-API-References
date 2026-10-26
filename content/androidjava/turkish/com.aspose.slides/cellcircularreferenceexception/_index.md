---
title: CellCircularReferenceException
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir formülün kendi hücresine doğrudan veya dolaylı olarak başvurduğu bir veya daha fazla dairesel referans tespit edildiğinde atılan istisna.
type: docs
url: /tr/com.aspose.slides/cellcircularreferenceexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

Formülün kendi hücresine doğrudan veya dolaylı olarak referans vermesi durumunda bir veya daha fazla dairesel referans tespit edildiğinde atılan istisna.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | Yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır. |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | Belirtilen hata mesajı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır. |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | Bu istisnanın nedeni olan iç istisnaya bir referans ve belirtilen hata mesajı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır. |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | Belirtilen hata mesajı ve dairesel hücre referansı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getReference()](#getReference--) | Dairesel bir hücre referansı alır. |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

Yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır.

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

Belirtilen hata mesajı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata hakkında açıklama içeren bir dize. |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

Belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisnaya bir referans ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata hakkında açıklama içeren bir dize. |
| innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna. |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

Belirtilen hata mesajı ve dairesel hücre referansı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata hakkında açıklama içeren bir dize. |
| reference | java.lang.String | Dairesel bir hücre referansı. |

### getReference() {#getReference--}
```
public final String getReference()
```

Dairesel bir hücre referansı alır.

**Döndürür:**
java.lang.String