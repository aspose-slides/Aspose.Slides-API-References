---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Etkili metin stili özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Değiştirilemez nesne, etkili metin stili özelliklerini içerir.

--------------------

Bu arayüz, [ITextStyle](../../com.aspose.slides/itextstyle) arayüzüyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Etkili stilin seviyesini döndürür. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Etkili varsayılan paragraf özelliklerini döndürür. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Etkili stilin seviyesini döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Düzeyin sıfır tabanlı indeksi. 0..8 aralığında olmalıdır. |

**Döndürür:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) seviyesinin etkili biçimlendirmesi.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Etkili varsayılan paragraf özelliklerini döndürür. Salt-okunur [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Döndürür:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)