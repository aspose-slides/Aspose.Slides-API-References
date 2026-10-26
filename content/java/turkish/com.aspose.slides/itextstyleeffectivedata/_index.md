---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Etkin metin stili özelliklerini içeren değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Etkin metin stili özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arabirim, [ITextStyle](../../com.aspose.slides/itextstyle) arabirimiyle birlikte, miras uygulanan etkili biçimlendirme değerlerini döndürmek için kullanılır.
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
| index | int | Seviyenin sıfır tabanlı indeksi. 0..8 aralığında olmalıdır. |

**Dönüş:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Seviye [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) için etkili biçimlendirme.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Etkili varsayılan paragraf özelliklerini döndürür. Salt-okunur [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Dönüş:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)