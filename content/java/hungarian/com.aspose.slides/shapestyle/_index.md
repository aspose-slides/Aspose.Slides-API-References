---
title: ShapeStyle
second_title: Aspose.Slides Java API hivatkozás
description: A shape stílusreferenciát ábrázolja.
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

A shape stílusreferenciáját képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getLineColor()](#getLineColor--) | Visszaadja a shape körvonal színét. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Visszaadja vagy beállítja a line oszlopindexét egy stílusmátrixon. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Visszaadja vagy beállítja a line oszlopindexét egy stílusmátrixon. |
| [getFillColor()](#getFillColor--) | Visszaadja a shape kitöltőszínét. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Visszaadja vagy beállítja a shape kitöltő oszlopindexét a stílusmátrixokban. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Visszaadja vagy beállítja a shape kitöltő oszlopindexét a stílusmátrixokban. |
| [getEffectColor()](#getEffectColor--) | Visszaadja a shape effektus színét. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Visszaadja vagy beállítja a shape effektus oszlopindexét egy stílusmátrixon. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Visszaadja vagy beállítja a shape effektus oszlopindexét egy stílusmátrixon. |
| [getFontColor()](#getFontColor--) | Visszaadja a shape betűszínét. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Visszaadja vagy beállítja a shape betűkészlet indexét egy betűkészlet gyűjteményben. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Visszaadja vagy beállítja a shape betűkészlet indexét egy betűkészlet gyűjteményben. |

### getLineColor() {#getLineColor--}
```
public final IColorFormat getLineColor()
```

Visszaadja a shape körvonal színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getLineStyleIndex() {#getLineStyleIndex--}
```
public final int getLineStyleIndex()
```

Visszaadja vagy beállítja a line oszlopindexét egy stílusmátrixon. Olvasás/írás int.

**Visszatér:**  
int

### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public final void setLineStyleIndex(int value)
```

Visszaadja vagy beállítja a line oszlopindexét egy stílusmátrixon. Olvasás/írás int.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFillColor() {#getFillColor--}
```
public final IColorFormat getFillColor()
```

Visszaadja a shape kitöltőszínét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFillStyleIndex() {#getFillStyleIndex--}
```
public final short getFillStyleIndex()
```

Visszaadja vagy beállítja a shape kitöltő oszlopindexét a stílusmátrixokban. 0 = nincs kitöltés, pozitív érték – index a téma kitöltési stílusaiban, negatív érték – index a téma háttérstílusaiban. Olvasás/írás short.

**Visszatér:**  
short

### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public final void setFillStyleIndex(short value)
```

Visszaadja vagy beállítja a shape kitöltő oszlopindexét a stílusmátrixokban. 0 = nincs kitöltés, pozitív érték – index a téma kitöltési stílusaiban, negatív érték – index a téma háttérstílusaiban. Olvasás/írás short.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | short |  |

### getEffectColor() {#getEffectColor--}
```
public final IColorFormat getEffectColor()
```

Visszaadja a shape effektus színét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public final long getEffectStyleIndex()
```

Visszaadja vagy beállítja a shape effektus oszlopindexét egy stílusmátrixon. Olvasás/írás long.

**Visszatér:**  
long

### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public final void setEffectStyleIndex(long value)
```

Visszaadja vagy beállítja a shape effektus oszlopindexét egy stílusmátrixon. Olvasás/írás long.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getFontColor() {#getFontColor--}
```
public final IColorFormat getFontColor()
```

Visszaadja a shape betűszínét. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatér:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public final byte getFontCollectionIndex()
```

Visszaadja vagy beállítja a shape betűkészlet indexét egy betűkészlet gyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Visszatér:**  
byte

### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public final void setFontCollectionIndex(byte value)
```

Visszaadja vagy beállítja a shape betűkészlet indexét egy betűkészlet gyűjteményben. Olvasás/írás [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |