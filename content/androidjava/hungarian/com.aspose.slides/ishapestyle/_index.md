---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: A forma stílusára vonatkozó hivatkozás.
type: docs
url: /hu/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

A forma stílusára vonatkozó hivatkozás.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLineColor()](#getLineColor--) | Visszaadja a forma körvonalának színét. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Visszaadja vagy beállítja a vonal stílusmátrixban lévő oszlopindexét. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Visszaadja vagy beállítja a vonal stílusmátrixban lévő oszlopindexét. |
| [getFillColor()](#getFillColor--) | Visszaadja a forma kitöltési színét. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. |
| [getEffectColor()](#getEffectColor--) | Visszaadja a forma effektus színét. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. |
| [getFontColor()](#getFontColor--) | Visszaadja a forma betűszínét. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Visszaadja vagy beállítja a forma betűtípus-indexét egy betűtípus-gyűjteményben. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Visszaadja vagy beállítja a forma betűtípus-indexét egy betűtípus-gyűjteményben. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Visszaadja a forma körvonalának színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Visszaadja vagy beállítja a vonal stílusmátrixban lévő oszlopindexét. Olvasás/írás int.

**Visszatérési érték:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Visszaadja vagy beállítja a vonal stílusmátrixban lévő oszlopindexét. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Visszaadja a forma kitöltési színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. 0 jelent kitöltés nélkül, pozitív érték – a téma kitöltési stílusainak indexe, negatív érték – a téma háttérstílusainak indexe. Olvasás/írás short.

**Visszatérési érték:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. 0 jelent kitöltés nélkül, pozitív érték – a téma kitöltési stílusainak indexe, negatív érték – a téma háttérstílusainak indexe. Olvasás/írás short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Visszaadja a forma effektus színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. Olvasás/írás long.

**Visszatérési érték:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Visszaadja a forma betűszínét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Visszaadja vagy beállítja a forma betűtípus-indexét egy betűtípus-gyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Visszatérési érték:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Visszaadja vagy beállítja a forma betűtípus-indexét egy betűtípus-gyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |