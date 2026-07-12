---
title: IOverridableText
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir grafik için geçersiz kılınabilir metni temsil eder.
type: docs
url: /tr/com.aspose.slides/ioverridabletext/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IOverridableText extends IFormattedTextContainer
```

Bir grafik için geçersiz kılınabilir metni temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Zengin biçimlendirilmiş bir metin içerebilir. |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. |

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public abstract ITextFrame getTextFrameForOverriding()
```

Zengin biçimlendirilmiş bir metin içerebilir. Bu özellik null değilse, bu biçimlendirilmiş metin değeri otomatik oluşturulan metni geçersiz kılar. Otomatik oluşturulan metin, veri etiketi, değer ekseninin gösterge birimi etiketi, eksen başlığı, grafik başlığı, trend çizgisi etiketi gibi unsurların örtük özelliğidir. Otomatik oluşturulan metin, IFormattedTextContainer.TextFormat özelliği ile biçimlendirilir. Yalnızca okuma [ITextFrame](../../com.aspose.slides/itextframe).

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public abstract ITextFrame addTextFrameForOverriding(String text)
```

TextFrameForOverriding'i parametre "text" içindeki metinle başlatır. TextFrameForOverriding zaten başlatılmışsa, yalnızca metnini değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | java.lang.String | Yeni bir TextFrameForOverriding için metin. |

**Döndürür:**
[ITextFrame](../../com.aspose.slides/itextframe) - Metin çerçevesi [ITextFrame](../../com.aspose.slides/itextframe)