---
title: CellInvalidFormulaException
second_title: Aspose.Slides için Java API Referansı
description: Hesaplanan formül doğru olmadığında veya ayrıştırılamadığında atılan istisna.
type: docs
url: /tr/com.aspose.slides/cellinvalidformulaexception/
---
**Kalıtım:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

Hesaplanan formül doğru olmadığında veya ayrıştırılamadığında atılan istisna.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini başlatır. |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini belirtilen hata mesajı ile başlatır. |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisnaya bir başvuru ile başlatır. |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve geçersiz formülü içeren bir hücre referansı ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getReference()](#getReference--) | Geçersiz formülü içeren bir hücre referansı alır. |
### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini başlatır.

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini belirtilen hata mesajı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hatayı açıklayan bir dize. |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisnaya bir başvuru ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hatayı açıklayan bir dize. |
| innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna. |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

[CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) sınıfının yeni bir örneğini belirtilen hata mesajı ve geçersiz formülü içeren bir hücre referansı ile başlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| message | java.lang.String | Hatayı açıklayan bir dize. |
| reference | java.lang.String | İç istisnaya bir referansı açıklayan bir dize. |

### getReference() {#getReference--}
```
public final String getReference()
```

Geçersiz formülü içeren bir hücre referansı alır.

**Döndürür:**
java.lang.String