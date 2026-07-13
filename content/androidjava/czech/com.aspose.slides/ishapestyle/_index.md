---
title: IShapeStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Represent shapes style reference.
type: docs
url: /cs/com.aspose.slides/ishapestyle/
---```
public interface IShapeStyle
```

Reprezentuje referenci stylu tvaru.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLineColor()](#getLineColor--) | Vrací barvu obrysu tvaru. |
| [getLineStyleIndex()](#getLineStyleIndex--) | Vrací nebo nastavuje index sloupce čáry ve stylové matici. |
| [setLineStyleIndex(int value)](#setLineStyleIndex-int-) | Vrací nebo nastavuje index sloupce čáry ve stylové matici. |
| [getFillColor()](#getFillColor--) | Vrací barvu výplně tvaru. |
| [getFillStyleIndex()](#getFillStyleIndex--) | Vrací nebo nastavuje index sloupce výplně tvaru ve stylových maticích. |
| [setFillStyleIndex(short value)](#setFillStyleIndex-short-) | Vrací nebo nastavuje index sloupce výplně tvaru ve stylových maticích. |
| [getEffectColor()](#getEffectColor--) | Vrací barvu efektu tvaru. |
| [getEffectStyleIndex()](#getEffectStyleIndex--) | Vrací nebo nastavuje index sloupce efektu ve stylové matici. |
| [setEffectStyleIndex(long value)](#setEffectStyleIndex-long-) | Vrací nebo nastavuje index sloupce efektu ve stylové matici. |
| [getFontColor()](#getFontColor--) | Vrací barvu písma tvaru. |
| [getFontCollectionIndex()](#getFontCollectionIndex--) | Vrací nebo nastavuje index písma tvaru ve sbírce písem. |
| [setFontCollectionIndex(byte value)](#setFontCollectionIndex-byte-) | Vrací nebo nastavuje index písma tvaru ve sbírce písem. |
### getLineColor() {#getLineColor--}
```
public abstract IColorFormat getLineColor()
```

Vrací barvu obrysu tvaru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getLineStyleIndex() {#getLineStyleIndex--}
```
public abstract int getLineStyleIndex()
```

Vrací nebo nastavuje index sloupce čáry ve stylové matici. Čtení a zápis int.

**Vrací:**
int
### setLineStyleIndex(int value) {#setLineStyleIndex-int-}
```
public abstract void setLineStyleIndex(int value)
```

Vrací nebo nastavuje index sloupce čáry ve stylové matici. Čtení a zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFillColor() {#getFillColor--}
```
public abstract IColorFormat getFillColor()
```

Vrací barvu výplně tvaru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFillStyleIndex() {#getFillStyleIndex--}
```
public abstract short getFillStyleIndex()
```

Vrací nebo nastavuje index sloupce výplně tvaru ve stylových maticích. 0 znamená žádnou výplň, kladná hodnota – index ve výplňových stylech motivu, záporná hodnota – index ve stylu pozadí motivu. Čtení a zápis short.

**Vrací:**
short
### setFillStyleIndex(short value) {#setFillStyleIndex-short-}
```
public abstract void setFillStyleIndex(short value)
```

Vrací nebo nastavuje index sloupce výplně tvaru ve stylových maticích. 0 znamená žádnou výplň, kladná hodnota – index ve výplňových stylech motivu, záporná hodnota – index ve stylu pozadí motivu. Čtení a zápis short.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | short |  |
### getEffectColor() {#getEffectColor--}
```
public abstract IColorFormat getEffectColor()
```

Vrací barvu efektu tvaru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffectStyleIndex() {#getEffectStyleIndex--}
```
public abstract long getEffectStyleIndex()
```

Vrací nebo nastavuje index sloupce efektu ve stylové matici. Čtení a zápis long.

**Vrací:**
long
### setEffectStyleIndex(long value) {#setEffectStyleIndex-long-}
```
public abstract void setEffectStyleIndex(long value)
```

Vrací nebo nastavuje index sloupce efektu ve stylové matici. Čtení a zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getFontColor() {#getFontColor--}
```
public abstract IColorFormat getFontColor()
```

Vrací barvu písma tvaru. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getFontCollectionIndex() {#getFontCollectionIndex--}
```
public abstract byte getFontCollectionIndex()
```

Vrací nebo nastavuje index písma tvaru ve sbírce písem. Čtení a zápis [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Vrací:**
byte
### setFontCollectionIndex(byte value) {#setFontCollectionIndex-byte-}
```
public abstract void setFontCollectionIndex(byte value)
```

Vrací nebo nastavuje index písma tvaru ve sbírce písem. Čtení a zápis [FontCollectionIndex](../../com.aspose.slides/fontcollectionindex).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |