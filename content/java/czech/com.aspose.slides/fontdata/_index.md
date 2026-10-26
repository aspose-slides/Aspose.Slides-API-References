---
title: FontData
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje definici písma.
type: docs
url: /cs/com.aspose.slides/fontdata/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

Reprezentuje definici písma. Neměnný.
## Konstruktorzy

| Konstruktor | Popis |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Vytvoří nový objekt FontData se zadaným názvem písma. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getFontName()](#getFontName--) | Vrací název písma. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Vrací název písma, přičemž nahrazuje odkaz na téma skutečným použittým písmem. |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dvě instance FontData rovny. |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hash tabulka. |
| [toString()](#toString--) | Vrací řetězcovou reprezentaci. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```

Vytvoří nový objekt FontData se zadaným názvem písma.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | java.lang.String | Název písma. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```

Vrací název písma. Čtení / zápis String.

**Vrací:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```

Vrací název písma, přičemž nahrazuje odkaz na téma skutečným použittým písmem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | Téma, ze kterého by měl být převzat název písma z tématu. Je na volajícím, aby poskytl správnou hodnotu. Viz [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Vrací:**
java.lang.String - Název písma.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda jsou dvě instance FontData rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | FontData, se kterou se má porovnat aktuální FontData. |

**Vrací:**
boolean - **true** pokud je zadaný FontData roven aktuálnímu FontData; jinak **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ, vhodná pro použití v hashovacích algoritmech a datových strukturách, jako je hash tabulka.

**Vrací:**
int - Hash kód FontData.
### toString() {#toString--}
```
public String toString()
```

Vrací řetězcovou reprezentaci.

**Vrací:**
java.lang.String - String reprezentace.