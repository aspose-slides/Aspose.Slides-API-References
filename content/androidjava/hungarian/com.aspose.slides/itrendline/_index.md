---
title: ITrendline
second_title: Aspose.Slides Androidra a Java API referenciájával
description: Az osztály a diagram sorozat trendvonalát képviseli
type: docs
url: /hu/com.aspose.slides/itrendline/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Az osztály a diagram sorozat trendvonalát képviseli
## Módszerek

| Method | Leírás |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | A trendvonal nevét adja vissza vagy állítja be. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | A trendvonal nevét adja vissza vagy állítja be. |
| [getTrendlineType()](#getTrendlineType--) | A trendvonal típusát adja vissza vagy állítja be. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | A trendvonal típusát adja vissza vagy állítja be. |
| [getFormat()](#getFormat--) | A trendvonal formátumát reprezentálja. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A trendvonal formátumát reprezentálja. |
| [getBackward()](#getBackward--) | A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak előtt nyújt. |
| [setBackward(double value)](#setBackward-double-) | A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak előtt nyújt. |
| [getForward()](#getForward--) | A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak után nyújt. |
| [setForward(double value)](#setForward-double-) | A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak után nyújt. |
| [getIntercept()](#getIntercept--) | A trendvonal y tengelyen való metszéspontjának értékét adja meg. |
| [setIntercept(double value)](#setIntercept-double-) | A trendvonal y tengelyen való metszéspontjának értékét adja meg. |
| [getDisplayEquation()](#getDisplayEquation--) | A trendvonalra vonatkozó egyenlet megjelenítését adja meg a diagramon (az Rsquaredvalue címkében). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | A trendvonalra vonatkozó egyenlet megjelenítését adja meg a diagramon (az Rsquaredvalue címkében). |
| [getOrder()](#getOrder--) | A polinomi trendvonal sorrendjét adja meg. |
| [setOrder(byte value)](#setOrder-byte-) | A polinomi trendvonal sorrendjét adja meg. |
| [getPeriod()](#getPeriod--) | A mozgó átlag trendvonal periódusát adja meg. |
| [setPeriod(byte value)](#setPeriod-byte-) | A mozgó átlag trendvonal periódusát adja meg. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | A trendvonal R-négyzett értékének megjelenítését adja meg a diagramon (az egyenlettel együtt). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | A trendvonal R-négyzett értékének megjelenítését adja meg a diagramon (az egyenlettel együtt). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Legend bejegyzést reprezentál, amely ehhez a trendvonalhoz kapcsolódik. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

A trendvonal nevét adja vissza vagy állítja be. Olvasás/írás String.

**Visszatér:**
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

**Visszatér:**
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

A trendvonal formátumát reprezentálja. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

A trendvonal formátumát reprezentálja. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak előtt nyújt. Szórt és nem szórt diagramoknál az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Visszatér:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak előtt nyújt. Szórt és nem szórt diagramoknál az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak után nyújt. Szórt és nem szórt diagramoknál az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Visszatér:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

A kategóriák (vagy szórt diagram esetén egységek) számát adja meg, amelyet a trendvonal a sorozat adatainak után nyújt. Szórt és nem szórt diagramoknál az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

A trendvonal y tengelyen való metszéspontjának értékét adja meg. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Olvasás/írás double.

**Visszatér:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

A trendvonal y tengelyen való metszéspontjának értékét adja meg. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

A trendvonalra vonatkozó egyenlet megjelenítését adja meg a diagramon (az Rsquaredvalue címkében). Olvasás/írás boolean.

**Visszatér:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

A trendvonalra vonatkozó egyenlet megjelenítését adja meg a diagramon (az Rsquaredvalue címkében). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

A polinomi trendvonal sorrendjét adja meg. Más típusú trendvonalaknál figyelmen kívül hagyott. Az értéknek 2 és 6 között kell lennie. Olvasás/írás byte.

**Visszatér:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

A polinomi trendvonal sorrendjét adja meg. Más típusú trendvonalaknál figyelmen kívül hagyott. Az értéknek 2 és 6 között kell lennie. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

A mozgó átlag trendvonal periódusát adja meg. Más trendvonal változatoknál figyelmen kívül hagyott. Az értéknek 2 és 255 között kell lennie. Olvasás/írás byte.

**Visszatér:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

A mozgó átlag trendvonal periódusát adja meg. Más trendvonal változatoknál figyelmen kívül hagyott. Az értéknek 2 és 255 között kell lennie. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

A trendvonal R-négyzett értékének megjelenítését adja meg a diagramon (az egyenlettel együtt). Olvasás/írás boolean.

**Visszatér:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

A trendvonal R-négyzett értékének megjelenítését adja meg a diagramon (az egyenlettel együtt). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Legend bejegyzést reprezentál, amely ehhez a trendvonalhoz kapcsolódik. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)