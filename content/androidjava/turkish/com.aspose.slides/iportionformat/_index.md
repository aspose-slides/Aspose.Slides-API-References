---
title: IPortionFormat
second_title: Aspose.Slides for Android için Java API Referansı
description: Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/iportionformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

Bu sınıf, metin bölümü biçimlendirme özelliklerini içerir. [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)'nin aksine, bu sınıfın tüm özellikleri yazılabilir.

--------------------

Bu sınıf, belirli bölüm için tanımlanan metin bölümü biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değer alınırken kalıtımın uygulanmadığı anlamına gelir; bu nedenle çoğu durumda "tanımsız" anlamına gelen değerler elde edersiniz.

Kalıtım dahil etkili biçimlendirme parametre değerlerini almak için [getEffective](../../com.aspose.slides/iportionformat\#getEffective) metodunu kullanmanız gerekir; bu metod bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) örneği döndürür.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Yer işareti tanımlayıcısını döndürür veya ayarlar. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Yer işareti tanımlayıcısını döndürür veya ayarlar. |
| [getSmartTagClean()](#getSmartTagClean--) | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Akıllı etiketin temizlenip temizlenmeyeceğini belirler. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili bölüm biçimlendirme verisini alır. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

Yer işareti tanımlayıcısını döndürür veya ayarlar. Okunur/Yazılır String.

**Döndürür:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

Yer işareti tanımlayıcısını döndürür veya ayarlar. Okunur/Yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır boolean.

**Döndürür:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

Akıllı etiketin temizlenip temizlenmeyeceğini belirler. Kalıtım uygulanmaz. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

Kalıtım uygulanmış etkili bölüm biçimlendirme verisini alır.

**Döndürür:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).