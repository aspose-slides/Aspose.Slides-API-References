---
title: IWarningCallback
second_title: Aspose.Slides for Java API Reference
description: Interface for classes which receive warning
type: docs
url: /tr/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Uyarı alan sınıflar için arayüz
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Uyarıyı alan ve işlemin iptal edilip edilmeyeceğine karar veren geri çağırma yöntemi. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Uyarıyı alan ve işlemin iptal edilip edilmeyeceğine karar veren geri çağırma yöntemi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | İşlenecek uyarı. |

**Döndürür:**
int - İptal kararı [ReturnAction](../../com.aspose.slides/returnaction).