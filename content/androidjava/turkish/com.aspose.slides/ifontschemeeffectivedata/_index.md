---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective font scheme properties.
type: docs
url: /tr/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

Etkili yazı tipi şeması özelliklerini içeren değiştirilemez nesne.

--------------------

Bu arayüz [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) parçası olarak kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMinor()](#getMinor--) | Slaytın "body" bölümüne ait yazı tipleri koleksiyonunu döndürür. |
| [getMajor()](#getMajor--) | Slaytın "heading" bölümüne ait yazı tipleri koleksiyonunu döndürür. |
| [getName()](#getName--) | Yazı tipi şeması adını döndürür. |

### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

Slaytın "body" bölümüne ait yazı tipleri koleksiyonunu döndürür. Yalnızca okuma [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Döndürür:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)

### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

Slaytın "heading" bölümüne ait yazı tipleri koleksiyonunu döndürür. Yalnızca okuma [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**Döndürür:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)

### getName() {#getName--}
```
public abstract String getName()
```

Yazı tipi şeması adını döndürür. Yalnızca okuma String.

**Döndürür:**
java.lang.String