---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /tr/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Metin stili biçimlendirme özellikleri.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Stilin seviyesi mevcutsa onu döndürür, aksi takdirde null döndürür. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Varsayılan paragraf özellikleri. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili metin stili biçimlendirme verilerini alır. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Stilin seviyesi mevcutsa onu döndürür, aksi takdirde null döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Düzeyin sıfır tabanlı indeksi. 0..8 aralığında olmalıdır. |

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - [IParagraphFormat](../../com.aspose.slides/iparagraphformat) seviyesinin biçimlendirmesi.
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

Varsayılan paragraf özellikleri. Salt okunur [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

Kalıtım uygulanmış etkili metin stili biçimlendirme verilerini alır.

**Döndürür:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Bir [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).