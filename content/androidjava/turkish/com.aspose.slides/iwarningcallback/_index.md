---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Uyarı alan sınıflar için arabirim
type: docs
url: /tr/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

Uyarı alan sınıflar için arabirim
## Methods

| Method | Description |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | Callback method which receives warning and decides whether operation should be aborted. |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

Uyarıyı alan ve işlemin iptal edilip edilmeyeceğine karar veren geri çağırma yöntemi.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | İşlenecek uyarı. |

**Dönüş Değeri:**
int - İptal kararı [ReturnAction](../../com.aspose.slides/returnaction).