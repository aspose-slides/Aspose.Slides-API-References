---
title: FontData
second_title: Java API Referansı üzerinden Android için Aspose.Slides
description: Bir font tanımını temsil eder.
type: docs
url: /tr/com.aspose.slides/fontdata/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Bir font tanımını temsil eder. Değiştirilemez.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Belirtilen font adıyla yeni bir FontData nesnesi oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFontName()](#getFontName--) | Font adını döndürür. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Font adını döndürür, tema referansını kullanılan gerçek font ile değiştirir. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki FontData örneğinin eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Belirli bir tip için hash işlevi olarak hizmet verir, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur. |
| [toString()](#toString--) | String temsili döndürür. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Belirtilen font adıyla yeni bir FontData nesnesi oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Font adı. |
### getFontName() {#getFontName--}
```
public final String getFontName()
```

Font adını döndürür. Okuma/yazma String.

**Döndürür:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Font adını döndürür, tema referansını kullanılan gerçek font ile değiştirir.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Font adının alınacağı tema. Doğru bir değer sağlamak çağıranın sorumluluğundadır. Bakınız [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Döndürür:**
java.lang.String - Font adı.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

İki FontData örneğinin eşit olup olmadığını belirler.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Mevcut FontData ile karşılaştırılacak FontData. |

**Döndürür:**
boolean - **true** eğer belirtilen FontData geçerli FontData ile eşitse; aksi takdirde **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Belirli bir tip için hash işlevi olarak hizmet verir, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygundur.

**Döndürür:**
int - FontData'nın hash kodu.
### toString() {#toString--}
```
public String toString()
```

String temsili döndürür.

**Döndürür:**
java.lang.String - String temsili.