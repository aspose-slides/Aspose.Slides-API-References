---
title: IWarningInfo
second_title: Aspose.Slides for Java API Referansı
description: Tüm uyarılar için temel bir arayüz temsil eder.
type: docs
url: /tr/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Tüm uyarılar için temel bir arayüz temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | receiver null değilse, belirtilen bir alıcıya uyarıyı sonlandırır ve alıcı işlemi iptal etmeye karar verirse AbortRequestedException fırlatır. |
| [getWarningType()](#getWarningType--) | Uyarının türünü döndürür. |
| [getDescription()](#getDescription--) | Bu uyarının insan tarafından okunabilir açıklamasını döndürür. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

receiver null değilse, belirtilen bir alıcıya uyarıyı sonlandırır ve alıcı işlemi iptal etmeye karar verirse AbortRequestedException fırlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Alıcı nesnesi [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Uyarının türünü döndürür. Salt-okunur [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Döndürür:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Bu uyarının insan tarafından okunabilir açıklamasını döndürür. Salt-okunur String.

**Döndürür:**
java.lang.String