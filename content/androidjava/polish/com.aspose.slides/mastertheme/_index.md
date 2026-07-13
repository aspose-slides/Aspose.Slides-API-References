---
title: MasterTheme
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Reprezentuje motyw główny.
type: docs
url: /pl/com.aspose.slides/mastertheme/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Theme](../../com.aspose.slides/theme)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMasterTheme](../../com.aspose.slides/imastertheme)
```
public final class MasterTheme extends Theme implements IMasterTheme
```

Reprezentuje motyw główny.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColorScheme()](#getColorScheme--) | Zwraca schemat kolorów. |
| [getFontScheme()](#getFontScheme--) | Zwraca schemat czcionek. |
| [getFormatScheme()](#getFormatScheme--) | Zwraca schemat formatu kształtu. |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | Zwraca kolekcję dodatkowych schematów kolorów. |
| [getName()](#getName--) | Zwraca nazwę motywu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca nazwę motywu. |
| [getVersion()](#getVersion--) |  |
### getColorScheme() {#getColorScheme--}
```
public IColorScheme getColorScheme()
```


Zwraca schemat kolorów. Tylko do odczytu [IColorScheme](../../com.aspose.slides/icolorscheme).

**Zwraca:**
[IColorScheme](../../com.aspose.slides/icolorscheme)
### getFontScheme() {#getFontScheme--}
```
public IFontScheme getFontScheme()
```


Zwraca schemat czcionek. Tylko do odczytu [IFontScheme](../../com.aspose.slides/ifontscheme).

**Zwraca:**
[IFontScheme](../../com.aspose.slides/ifontscheme)
### getFormatScheme() {#getFormatScheme--}
```
public IFormatScheme getFormatScheme()
```


Zwraca schemat formatu kształtu. Tylko do odczytu [IFormatScheme](../../com.aspose.slides/iformatscheme).

**Zwraca:**
[IFormatScheme](../../com.aspose.slides/iformatscheme)
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public final IExtraColorSchemeCollection getExtraColorSchemes()
```


Zwraca kolekcję dodatkowych schematów kolorów. Te schematy nie wpływają na wygląd prezentacji, mogą być wybrane jako główny schemat kolorów dla slajdu. Tylko do odczytu [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**Zwraca:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public final String getName()
```


Zwraca nazwę motywu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Zwraca nazwę motywu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long