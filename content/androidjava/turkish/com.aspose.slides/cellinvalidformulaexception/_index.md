---
title: CellInvalidFormulaException
second_title: Aspose.Slides for Android için Java API Referansı
description: Hesaplanan bir formül doğru olmadığında veya ayrıştırılamadığında fırlatılan istisna.
type: docs
url: /tr/com.aspose.slides/cellinvalidformulaexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Hesaplanan bir formül doğru olmadığında veya ayrıştırılamadığında fırlatılan istisna.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği başlatır. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği belirtilen hata mesajı ile başlatır. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile başlatır. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği belirtilen hata mesajı ve geçersiz formülü içeren hücre referansı ile başlatır. |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getReference()](#getReference--) | Geçersiz formülü içeren hücre referansını alır. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği başlatır.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği belirtilen hata mesajı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hatayı tanımlayan dize. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hatayı tanımlayan dize. |
| innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

Yeni bir [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfı örneği belirtilen hata mesajı ve geçersiz formülü içeren hücre referansı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hatayı tanımlayan dize. |
| reference | java.lang.String | İç istisnaya bir referansı tanımlayan dize. |

### getReference() {#getReference--}
```
public final String getReference()
```

Geçersiz formülü içeren hücre referansını alır.

**Döndürür:**
java.lang.String