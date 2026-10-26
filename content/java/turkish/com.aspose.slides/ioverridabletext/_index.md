---
title: IOverridableText
second_title: Aspose.Slides for Java API Referansı
description: Bir grafik için geçersiz kılınabilir metni temsil eder.
type: docs
url: /tr/com.aspose.slides/ioverridabletext/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Bir grafik için geçersiz kılınabilir metni temsil eder.
## Metotlar

| Method | Description |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş bir metin içerebilir. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding'i "text" parametresindeki metinle başlatır. |
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Zengin biçimlendirilmiş bir metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri otomatik oluşturulan metni geçersiz kılar. Otomatik oluşturulan metin, veri etiketi, değer ekseninin gösterge birimi etiketi, eksen başlığı, grafik başlığı, trend çizgisi etiketi gibi örtük bir özelliktir. Otomatik oluşturulan metin, IFormattedTextContainer.TextFormat özelliğiyle biçimlendirilir. Salt okunur [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding'i "text" parametresindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa, sadece metnini değiştirir.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Yeni bir TextFrameForOverriding için metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe) - Metin çerçevesi [ITextFrame](../../com.aspose.slides/itextframe)