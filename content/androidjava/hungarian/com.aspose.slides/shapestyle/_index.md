---
title: ShapeStyle
second_title: Aspose.Slides Androidhoz a Java API hivatkozásával
description: A formák stílusreferenciáját ábrázolja.
type: docs
url: /hu/com.aspose.slides/shapestyle/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IShapeStyle](../../com.aspose.slides/ishapestyle)
```
public class ShapeStyle extends DomObject<Shape> implements IShapeStyle
```

A forma stílusreferenciáját ábrázolja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLineColor()](#getLineColor--) | Visszatér egy forma körvonal színével. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Visszaadja vagy beállítja a vonal oszlopindexét egy stílus mátrixban. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Visszaadja vagy beállítja a vonal oszlopindexét egy stílus mátrixban. |
| [getFillColor()](#getFillColor--) | Visszatér egy forma kitöltési színével. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílus mátrixokban. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílus mátrixokban. |
| [getEffectColor()](#getEffectColor--) | Visszatér egy forma effektus színével. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílus mátrixban. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Visszaadja vagy beállítja a forma efektus oszlopindexét egy stílus mátrixban. |
| [getFontColor()](#getFontColor--) | Visszatér egy forma betűszínével. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Visszaadja vagy beállítja a forma betű indexét egy betűgyűjteményben. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Visszaadja vagy beállítja a forma betű indexét egy betűgyűjteményben. |
### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

Visszatér egy forma körvonal színével. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

Visszaadja vagy beállítja a vonal oszlopindexét egy stílus mátrixban. Olvasás/írás int.

**Visszatér:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

Visszaadja vagy beállítja a vonal oszlopindexét egy stílus mátrixban. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

Visszatér egy forma kitöltési színével. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílus mátrixokban. 0 jelenti a kitöltés hiányát, pozitív érték – index a téma kitöltési stílusaiban, negatív érték – index a téma háttérstílusaiban. Olvasás/írás short.

**Visszatér:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílus mátrixokban. 0 jelenti a kitöltés hiányát, pozitív érték – index a téma kitöltési stílusaiban, negatív érték – index a téma háttérstílusaiban. Olvasás/írás short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

Visszatér egy forma effektus színével. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílus mátrixban. Olvasás/írás long.

**Visszatér:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílus mátrixban. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

Visszatér egy forma betűszínével. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

Visszaadja vagy beállítja a forma betű indexét egy betűgyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Visszatér:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

Visszaadja vagy beállítja a forma betű indexét egy betűgyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |