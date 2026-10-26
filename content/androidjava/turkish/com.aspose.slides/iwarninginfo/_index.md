---
title: IWarningInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a base interface for all warnings.
type: docs
url: /tr/com.aspose.slides/iwarninginfo/
---```
public interface IWarningInfo
```

Tüm uyarılar için temel bir arabirimi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [sendWarning(IWarningCallback receiver)](#sendWarning-com.aspose.slides.IWarningCallback-) | Eğer receiver null değilse, uyarıyı belirtilen alıcıya sonlandırır ve alıcı işlemi iptal etmeye karar verirse AbortRequestedException fırlatır. |
| [getWarningType()](#getWarningType--) | Uyarının tipini döndürür. |
| [getDescription()](#getDescription--) | Bu uyarının insan tarafından okunabilir açıklamasını döndürür. |
### sendWarning(IWarningCallback receiver) {#sendWarning-com.aspose.slides.IWarningCallback-}
```
public abstract void sendWarning(IWarningCallback receiver)
```

Eğer receiver null değilse, uyarıyı belirtilen alıcıya sonlandırır ve alıcı işlemi iptal etmeye karar verirse AbortRequestedException fırlatır.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| receiver | [IWarningCallback](../../com.aspose.slides/iwarningcallback) | Alıcı nesnesi [IWarningCallback](../../com.aspose.slides/iwarningcallback) |

### getWarningType() {#getWarningType--}
```
public abstract int getWarningType()
```

Uyarının tipini döndürür. Salt Okunur [WarningType](../../com.aspose.slides/warningtype)(\#getWarningType.getWarningType).

**Döndürür:**
int
### getDescription() {#getDescription--}
```
public abstract String getDescription()
```

Bu uyarının insan tarafından okunabilir açıklamasını döndürür. Salt Okunur String.

**Döndürür:**
java.lang.String