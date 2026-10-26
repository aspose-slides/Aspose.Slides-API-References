---
title: FontSubstitutionInfo
second_title: Aspose.Slides för Android via Java API-referens
description: Denna struktur representerar informationen om teckensnittsbyte när den kommer att renderas.
type: docs
url: /sv/com.aspose.slides/fontsubstitutioninfo/
---
**Arv:**
java.lang.Object
```
public class FontSubstitutionInfo
```

Denna struktur representerar informationen om teckensnittsbyte när den kommer att renderas.

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
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | Skapar en instans av [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | Anger källteckensnittets namn i presentationen. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | Anger ersättningsteckensnittets namn för det ursprungliga teckensnittet. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


Skapar en instans av [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) klass.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originFontName | java.lang.String | Källteckensnittets namn i presentationen String |
| substFontName | java.lang.String | Ersättningsteckensnittets namn för det ursprungliga teckensnittet String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


Anger källteckensnittets namn i presentationen. Skrivskyddad String

**Returnerar:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


Anger ersättningsteckensnittets namn för det ursprungliga teckensnittet. Skrivskyddad String

**Returnerar:**
java.lang.String