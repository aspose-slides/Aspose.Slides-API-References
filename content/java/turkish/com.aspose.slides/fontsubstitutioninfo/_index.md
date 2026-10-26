---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Java API Referansı
description: Bu yapı, yazı tipi değişiminin ne zaman render edileceği hakkında bilgileri temsil eder.
type: docs
url: /tr/com.aspose.slides/fontsubstitutioninfo/
---
**Kalıtım:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Bu yapı, yazı tipinin değişiminin ne zaman render edileceği hakkında bilgileri temsil eder.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Bir [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) sınıfının bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Sunumdaki kaynak yazı tipi adını gösterir. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Orijinal yazı tipi için değiştirme yazı tipi adını gösterir. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Bir [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) sınıfının bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| originFontName | java.lang.String | Sunumdaki kaynak yazı tipi adı String |
| substFontName | java.lang.String | Orijinal yazı tipi için değiştirme yazı tipi adı String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Sunumdaki kaynak yazı tipi adını gösterir. Salt okunur String

**Döndürür:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Orijinal yazı tipi için değiştirme yazı tipi adını gösterir. Salt okunur String

**Döndürür:**
java.lang.String