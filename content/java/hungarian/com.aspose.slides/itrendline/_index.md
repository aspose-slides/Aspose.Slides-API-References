---
title: ITrendline
second_title: Aspose.Slides Java API referencia
description: Az osztály a diagram sorozat trendvonalát képviseli.
type: docs
url: /hu/com.aspose.slides/itrendline/
---
**All Implemented Interfaces:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Az osztály a diagram sorozat trendvonalát képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | A trendvonal nevét adja vissza vagy állítja be. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | A trendvonal nevét adja vissza vagy állítja be. |
| [getTrendlineType()](#getTrendlineType--) | A trendvonal típusát adja vissza vagy állítja be. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | A trendvonal típusát adja vissza vagy állítja be. |
| [getFormat()](#getFormat--) | A trendvonal formátumát jelöli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A trendvonal formátumát jelöli. |
| [getBackward()](#getBackward--) | Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak előtt kiterjeszt. |
| [setBackward(double value)](#setBackward-double-) | Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak előtt kiterjeszt. |
| [getForward()](#getForward--) | Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak után kiterjeszt. |
| [setForward(double value)](#setForward-double-) | Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak után kiterjeszt. |
| [getIntercept()](#getIntercept--) | Megadja azt az értéket, ahol a trendvonal metszi az y tengelyt. |
| [setIntercept(double value)](#setIntercept-double-) | Megadja azt az értéket, ahol a trendvonal metszi az y tengelyt. |
| [getDisplayEquation()](#getDisplayEquation--) | Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az R-négyzet érték). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az R-négyzet érték). |
| [getOrder()](#getOrder--) | Megadja a polinom trendvonal rendjét. |
| [setOrder(byte value)](#setOrder-byte-) | Megadja a polinom trendvonal rendjét. |
| [getPeriod()](#getPeriod--) | Megadja a mozgóátlag trendvonal időszakát. |
| [setPeriod(byte value)](#setPeriod-byte-) | Megadja a mozgóátlag trendvonal időszakát. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A legend bejegyzést jelöli, amely ehhez a trendvonalhoz kapcsolódik, csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

A trendvonal nevét adja vissza vagy állítja be. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

A trendvonal nevét adja vissza vagy állítja be. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

A trendvonal típusát adja vissza vagy állítja be. Olvasás/írás [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Visszatérési érték:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

A trendvonal típusát adja vissza vagy állítja be. Olvasás/írás [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

A trendvonal formátumát jelöli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

A trendvonal formátumát jelöli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak előtt kiterjeszt. Szórás- és nem-szórás diagramok esetén az értéknek non-negative értéknek kell lennie. Olvasás/írás double.

**Visszatérési érték:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak előtt kiterjeszt. Szórás- és nem-szórás diagramok esetén az értéknek non-negative értéknek kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak után kiterjeszt. Szórás- és nem-szórás diagramok esetén az értéknek non-negative értéknek kell lennie. Olvasás/írás double.

**Visszatérési érték:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Megadja a kategóriák (vagy szórásdiagramon lévő egységek) számát, amelyet a trendvonal a trendelt sorozat adatainak után kiterjeszt. Szórás- és nem-szórás diagramok esetén az értéknek non-negative értéknek kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Megadja azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, lineáris vagy polinomiális. Olvasás/írás double.

**Visszatérési érték:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Megadja azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, lineáris vagy polinomiális. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az R-négyzet érték). Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Megadja, hogy a trendvonal egyenlete megjelenik a diagramon (ugyanabban a címkében, mint az R-négyzet érték). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Megadja a polinom trendvonal rendjét. Más trendvonal típusok esetén figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie. Olvasás/írás byte.

**Visszatérési érték:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Megadja a polinom trendvonal rendjét. Más trendvonal típusok esetén figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Megadja a mozgóátlag trendvonal időszakát. Más trendvonal változatok esetén figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie. Olvasás/írás byte.

**Visszatérési érték:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Megadja a mozgóátlag trendvonal időszakát. Más trendvonal változatok esetén figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). Olvasás/írás boolean.

**Visszatérési érték:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Megadja, hogy a trendvonal R-négyzet értéke megjelenik a diagramon (ugyanabban a címkében, mint az egyenlet). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

A legend bejegyzést jelöli, amely ehhez a trendvonalhoz kapcsolódik, csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatérési érték:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)