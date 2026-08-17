---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Metin stili biçimlendirme özellikleri.
type: docs
url: /tr/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Metin stili biçimlendirme özellikleri.
## Yöntemler

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Stil seviyesi mevcutsa onu döndürür, aksi takdirde null döndürür. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Varsayılan paragraf özellikleri. |
| [getEffective()](#getEffective--) | Kalıtım uygulandığında etkili metin stili biçimlendirme verilerini alır. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

Stil seviyesi mevcutsa onu döndürür, aksi takdirde null döndürür.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Seviye için sıfır temelli indeks. 0..8 aralığında olmalıdır. |

**Döndürür:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Seviye [IParagraphFormat](../../com.aspose.slides/iparagraphformat) biçimlendirmesi.
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

Kalıtım uygulandığında etkili metin stili biçimlendirme verilerini alır.

**Döndürür:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - Bir [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).