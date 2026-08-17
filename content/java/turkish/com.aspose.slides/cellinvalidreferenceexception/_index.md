---
title: CellInvalidReferenceException
second_title: Aspose.Slides for Java API Referansı
description: Geçersiz bir hücre referansı karşılaşıldığında fırlatılan istisna.
type: docs
url: /tr/com.aspose.slides/cellinvalidreferenceexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Geçersiz bir hücre referansı karşılaşıldığında fırlatılan istisna.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | Yeni bir [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının örneğini başlatır. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | Belirtilen bir hata mesajı ile yeni bir [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının örneğini başlatır. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | Belirtilen bir hata mesajı ve bu istisnanın nedeni olan iç istisnaya bir referans ile yeni bir [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının örneğini başlatır. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | Belirtilen bir hata mesajı ve geçersiz bir hücre referansı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır. |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getReference()](#getReference--) | Geçersiz bir hücre referansı alır. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

Yeni bir [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının örneğini başlatır.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

Belirtilen bir hata mesajı ile yeni bir [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata hakkında açıklama yapan bir dize. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

Belirtilen bir hata mesajı ve bu istisnanın nedeni olan iç istisnaya bir referans ile yeni bir [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata hakkında açıklama yapan bir dize. |
| innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

Belirtilen bir hata mesajı ve geçersiz bir hücre referansı ile yeni bir [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının örneğini başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hata hakkında açıklama yapan bir dize. |
| reference | java.lang.String | Geçersiz bir hücre referansı. |

### getReference() {#getReference--}
```
public final String getReference()
```

Geçersiz bir hücre referansı alır.

**Döndürür:**
java.lang.String