---
title: IFindResultCallback
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to getting search text result.
type: docs
url: /tr/com.aspose.slides/ifindresultcallback/
---```
public interface IFindResultCallback
```

Arama metni sonucunu elde etmek için kullanılan geri çağırma arayüzü.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)](#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-) | Bulunan metinle ilgili verileri alan geri çağırma yöntemi. |
### foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition) {#foundResult-com.aspose.slides.ITextFrame-java.lang.String-java.lang.String-int-}
```
public abstract void foundResult(ITextFrame textFrame, String sourceText, String foundText, int textPosition)
```

Bulunan metinle ilgili verileri alan geri çağırma yöntemi.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| textFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Metnin bulunduğu [ITextFrame](../../com.aspose.slides/itextframe). |
| sourceText | java.lang.String | Metnin bulunduğu kaynak metin. |
| foundText | java.lang.String | Bulunan metin. |
| textPosition | int | Bulunan metnin konumu. |