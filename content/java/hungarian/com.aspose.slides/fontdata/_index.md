---
title: FontData
second_title: Aspose.Slides Java API referencia
description: Betűtípusdefiníciót képvisel.
type: docs
url: /hu/com.aspose.slides/fontdata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

A betűtípus definíciót képviseli. Nem módosítható.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Creates a new FontData object with the specified font name. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFontName()](#getFontName--) | Visszaadja a betűtípus nevét. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Visszaadja a betűtípus nevét, a téma hivatkozást lecserélve a ténylegesen használt betűtípusra. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy két FontData példány egyenlő-e. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra. |
| [toString()](#toString--) | Visszaadja a karakterlánc ábrázolását. |
### FontData(String fontName) {#FontData-java.lang.String-}
```
public FontData(String fontName)
```


Új FontData objektumot hoz létre a megadott betűtípus névvel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | java.lang.String | Betűtípus neve. |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


Visszaadja a betűtípus nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### getFontName(IThemeEffectiveData theme) {#getFontName-com.aspose.slides.IThemeEffectiveData-}
```
public final String getFontName(IThemeEffectiveData theme)
```


Visszaadja a betűtípus nevét, a téma hivatkozást lecserélve a ténylegesen használt betűtípusra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | A téma, amelyből a tematikus betűtípusnevet kell venni. A hívónak kell biztosítania a helyes értéket. Lásd [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Visszatér:**
java.lang.String – Betűtípus neve.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy két FontData példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A jelenlegi FontData-vel összehasonlítandó FontData. |

**Visszatér:**
boolean – **true**, ha a megadott FontData egyenlő a jelenlegi FontData-val; egyébként **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatstruktúrákban, például hash táblában való használatra.

**Visszatér:**
int – A FontData hash kódja.
### toString() {#toString--}
```
public String toString()
```


Visszaadja a karakterlánc ábrázolását.

**Visszatér:**
java.lang.String – String reprezentáció.