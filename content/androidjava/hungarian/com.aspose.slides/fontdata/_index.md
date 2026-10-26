---
title: FontData
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy betűtípusdefiníciót ábrázol.
type: docs
url: /hu/com.aspose.slides/fontdata/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IFontData](../../com.aspose.slides/ifontdata)
```
public final class FontData implements IFontData
```

A betűtípusdefiníciót reprezentálja. Változtathatatlan.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [FontData(String fontName)](#FontData-java.lang.String-) | Új FontData objektumot hoz létre a megadott betűtípus névvel. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFontName()](#getFontName--) | Visszaadja a betűtípus nevét. |
| [getFontName(IThemeEffectiveData theme)](#getFontName-com.aspose.slides.IThemeEffectiveData-) | Visszaadja a betűtípus nevét, lecserélve a téma hivatkozást a ténylegesen használt betűtípusra. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a két FontData példány egyenlő-e. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatszerkezetekben, például hash táblázatban való használatra. |
| [toString()](#toString--) | Visszaadja a karakterlánc reprezentációt. |
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

Visszaadja a betűtípus nevét, lecserélve a téma hivatkozást a ténylegesen használt betűtípusra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| theme | [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata) | A téma, amelyből a témához tartozó betűtípus nevet kell venni. A hívó feladata, hogy helyes értéket biztosítson. Lásd [IThemeable.createThemeEffective](../../com.aspose.slides/ithemeable\#createThemeEffective) |

**Visszatér:**
java.lang.String - Betűtípus neve.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a két FontData példány egyenlő-e.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A FontData, amelyet az aktuális FontData-val kell összehasonlítani. |

**Visszatér:**
boolean - **true** ha a megadott FontData egyenlő az aktuális FontData-val; egyébként **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz, amely alkalmas hash algoritmusokban és adatszerkezetekben, például hash táblázatban való használatra.

**Visszatér:**
int - A FontData hash kódja.
### toString() {#toString--}
```
public String toString()
```

Visszaadja a karakterlánc reprezentációt.

**Visszatér:**
java.lang.String - Karakterlánc reprezentáció.