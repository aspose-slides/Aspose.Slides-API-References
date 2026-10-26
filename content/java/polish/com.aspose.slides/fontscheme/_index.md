---
title: FontScheme
second_title: Aspose.Slides dla Java – referencja API
description: Przechowuje czcionki zdefiniowane w motywie.
type: docs
url: /pl/com.aspose.slides/fontscheme/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

Przechowuje czcionki zdefiniowane w motywie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getMinor()](#getMinor--) | Returns the fonts collection for a "body" part of the slide. |
| [getMajor()](#getMajor--) | Returns the fonts collection for a "heading" part of the slide. |
| [getName()](#getName--) | Returns the font scheme name. |
| [setName(String value)](#setName-java.lang.String-) | Returns the font scheme name. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```

Zwraca kolekcję czcionek dla części "body" slajdu. Tylko do odczytu [IFonts](../../com.aspose.slides/ifonts).

**Zwraca:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```

Zwraca kolekcję czcionek dla części "heading" slajdu. Tylko do odczytu [IFonts](../../com.aspose.slides/ifonts).

**Zwraca:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```

Zwraca nazwę schematu czcionek. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

Zwraca nazwę schematu czcionek. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject