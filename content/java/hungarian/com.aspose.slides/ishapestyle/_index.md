---
title: IShapeStyle
second_title: Aspose.Slides for Java API Reference
description: A forma stílusreferenciáját ábrázolja.
type: docs
url: /hu/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

A forma stílusreferenciáját ábrázolja.
## Metódusok

| Method | Description |
| --- | --- |
| [getLineColor()](#getLineColor--) | Visszaadja a forma körvonal színét. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Visszaadja vagy beállítja a vonal oszlopindexét egy stílusmátrixban. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Visszaadja vagy beállítja a vonal oszlopindexét egy stílusmátrixban. |
| [getFillColor()](#getFillColor--) | Visszaadja a forma kitöltési színét. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. |
| [getEffectColor()](#getEffectColor--) | Visszaadja a forma effektus színét. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. |
| [getFontColor()](#getFontColor--) | Visszaadja a forma betűszínét. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Visszaadja vagy beállítja a forma betűtípus-indexet egy betűtípus-gyűjteményben. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Visszaadja vagy beállítja a forma betűtípus-indexet egy betűtípus-gyűjteményben. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Visszaadja a forma körvonal színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Visszaadja vagy beállítja a vonal oszlopindexét egy stílusmátrixban. Olvasás/írás int.

**Visszatér:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Visszaadja vagy beállítja a vonal oszlopindexét egy stílusmátrixban. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Visszaadja a forma kitöltési színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. 0 jelentése nincs kitöltés, pozitív érték – index a téma kitöltési stílusaiban, negatív érték – index a téma háttérstílusaiban. Olvasás/írás short.

**Visszatér:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Visszaadja vagy beállítja a forma kitöltési oszlopindexét a stílusmátrixokban. 0 jelentése nincs kitöltés, pozitív érték – index a téma kitöltési stílusaiban, negatív érték – index a téma háttérstílusaiban. Olvasás/írás short.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Visszaadja a forma effektus színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Visszaadja vagy beállítja a forma effektus oszlopindexét egy stílusmátrixban. Olvasás/írás long.

**Visszatér:**
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

**Visszatér:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Visszaadja vagy beállítja a forma betűtípus-indexet egy betűtípus-gyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Visszatér:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Visszaadja vagy beállítja a forma betűtípus-indexet egy betűtípus-gyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |