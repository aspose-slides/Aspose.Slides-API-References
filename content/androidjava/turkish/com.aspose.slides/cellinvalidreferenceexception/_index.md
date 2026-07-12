---
title: CellInvalidReferenceException
second_title: Aspose.Slides for Android Java API Referansı
description: Geçersiz bir hücre referansı karşılaşıldığında atılan istisna.
type: docs
url: /tr/com.aspose.slides/cellinvalidreferenceexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

Geçersiz bir hücre referansıyle karşılaşıldığında atılan istisna.
## Yapıcılar

| Constructor | Description |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının yeni bir örneğini oluşturur. |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının belirtilen hata mesajı ile yeni bir örneğini oluşturur. |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir örneğini oluşturur. |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının belirtilen hata mesajı ve geçersiz bir hücre referansı ile yeni bir örneğini oluşturur. |
## Yöntemler

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | Geçersiz bir hücre referansı alır. |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının yeni bir örneğini oluşturur.

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının belirtilen hata mesajı ile yeni bir örneğini oluşturur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Hata açıklamasını içeren bir dize. |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

[CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) sınıfının belirtilen hata mesajı ve bu istisnanın nedeni olan iç istisna referansı ile yeni bir örneğini oluşturur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Hata açıklamasını içeren bir dize. |
| innerException | java.lang.RuntimeException | Mevcut istisnanın nedeni olan istisna. |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

[CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) sınıfının belirtilen hata mesajı ve geçersiz bir hücre referansı ile yeni bir örneğini oluşturur.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Hata açıklamasını içeren bir dize. |
| reference | java.lang.String | Geçersiz bir hücre referansı. |

### getReference() {#getReference--}
```
public final String getReference()
```

Geçersiz bir hücre referansı alır.

**Döndürür:**
java.lang.String