---
title: IFindResultCallback
second_title: Aspose.Slides for Java API Reference
description: Arama metni sonucunu almak için kullanılan geri çağırma arabirimi.
type: docs
url: /tr/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Arama metni sonucunu almak için kullanılan geri çağırma arabirimi.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Bulunan metin hakkında veri alan geri çağırma yöntemi. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```


Bulunan metin hakkında veri alan geri çağırma yöntemi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Metnin bulunduğu [ITextFrame](../../com.aspose.slides/itextframe). |
| sourceText | java.lang.String | Metnin bulunduğu kaynak metin. |
| foundText | java.lang.String | Bulunan metin. |
| textPosition | int | Bulunan metnin konumu. |