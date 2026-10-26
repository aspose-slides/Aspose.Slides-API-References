---
title: FontSubstitutionInfo
second_title: Aspose.Slides for Android için Java API Referansı
description: Bu yapı, render edildiğinde yazı tipi değişikliğine ilişkin bilgileri temsil eder.
type: docs
url: /tr/com.aspose.slides/fontsubstitutioninfo/
---
**Kalıtım:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Bu yapı, render edildiğinde yazı tipi değiştirilmesiyle ilgili bilgileri temsil eder.

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
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) sınıfının bir örneğini oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Sunumda kaynak yazı tipi adını belirtir. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Orijinal yazı tipi için değiştirilen yazı tipi adını belirtir. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```

[FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) sınıfının bir örneğini oluşturur.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| originFontName | java.lang.String | Sunumda kaynak yazı tipi adı String |
| substFontName | java.lang.String | Orijinal yazı tipi için değiştirilen yazı tipi adı String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```

Sunumda kaynak yazı tipi adını belirtir. Yalnızca okuma String

**Döndürür:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```

Orijinal yazı tipi için değiştirilen yazı tipi adını belirtir. Yalnızca okuma String

**Döndürür:**
java.lang.String