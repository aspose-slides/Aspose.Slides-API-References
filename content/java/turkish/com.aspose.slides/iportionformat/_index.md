---
title: IPortionFormat
second_title: Aspose.Slides Java API Referansı
description: Bu sınıf, metin kısmı biçimlendirme özelliklerini içerir.
type: docs
url: /tr/com.aspose.slides/iportionformat/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBasePortionFormat](../../com.aspose.slides/ibaseportionformat), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IPortionFormat extends IBasePortionFormat, IHyperlinkContainer
```

This class contains the text portion formatting properties. Unlike [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

--------------------

Bu sınıf, belirli bölüm için tanımlanan metin kısmı biçimlendirme özelliklerini döndürmek ve değiştirmek için kullanılır. Bu, değerler alınırken kalıtımın uygulanmadığı anlamına gelir; bu yüzden çoğu durumda "tanımsız" anlamına gelen değerler alırsınız.

Kalıtım dahil olmak üzere etkili biçimlendirme parametre değerlerini almak için [getEffective](../../com.aspose.slides/iportionformat\#getEffective) metodunu kullanmanız gerekir; bu metod bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) örneği döndürür.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns or sets bookmark identifier. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returns or sets bookmark identifier. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determines whether the smart tag should be cleaned. |
| [getEffective()](#getEffective--) | Gets effective portion formatting data with the inheritance applied. |
### getBookmarkId() {#getBookmarkId--}
```
public abstract String getBookmarkId()
```

**Döndürür:**  
java.lang.String

**Returns or sets bookmark identifier. Read/write String.**  
**Döndürür:**  
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public abstract void setBookmarkId(String value)
```

**Returns or sets bookmark identifier. Read/write String.**  

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public abstract boolean getSmartTagClean()
```

**Kalıtım uygulanmaz.** Determines whether the smart tag should be cleaned. Okuma/Yazma boolean.

**Döndürür:**  
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public abstract void setSmartTagClean(boolean value)
```

**Kalıtım uygulanmaz.** Determines whether the smart tag should be cleaned. Okuma/Yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public abstract IPortionFormatEffectiveData getEffective()
```

**Kalıtım uygulanmış etkili bölüm biçimlendirme verilerini alır.**  

**Döndürür:**  
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Bir [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).