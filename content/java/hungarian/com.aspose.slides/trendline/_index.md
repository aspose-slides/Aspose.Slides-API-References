---
title: Trendline
second_title: Aspose.Slides for Java API referencia
description: Az osztály a diagram sorozat trendvonalát képviseli
type: docs
url: /hu/com.aspose.slides/trendline/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Az osztály a diagram sorozat trendvonalát képviseli
## Módszerek

| Method | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | A trendvonal nevét adja vissza vagy állítja be. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | A trendvonal nevét adja vissza vagy állítja be. |
| [getTrendlineType()](#getTrendlineType--) | A trendvonal típusát adja vissza vagy állítja be. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | A trendvonal típusát adja vissza vagy állítja be. |
| [getFormat()](#getFormat--) | A trendvonal formátumát képviseli. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A trendvonal formátumát képviseli. |
| [getBackward()](#getBackward--) | Meghatározza, hogy a trendvonal hány kategóriát (vagy egységet a szórt diagramon) nyújt ki a sorozat adatainak előtt. |
| [setBackward(double value)](#setBackward-double-) | Meghatározza, hogy a trendvonal hány kategóriát (vagy egységet a szórt diagramon) nyújt ki a sorozat adatainak előtt. |
| [getForward()](#getForward--) | Meghatározza, hogy a trendvonal hány kategóriát (vagy egységet a szórt diagramon) nyújt ki a sorozat adatainak után. |
| [setForward(double value)](#setForward-double-) | Meghatározza, hogy a trendvonal hány kategóriát (vagy egységet a szórt diagramon) nyújt ki a sorozat adatainak után. |
| [getIntercept()](#getIntercept--) | Meghatározza a trendvonal y tengely metszéspontjának értékét. |
| [setIntercept(double value)](#setIntercept-double-) | Meghatározza a trendvonal y tengely metszéspontjának értékét. |
| [getDisplayEquation()](#getDisplayEquation--) | Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (az Rsquaredvalue címkével együtt). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (az Rsquaredvalue címkével együtt). |
| [getOrder()](#getOrder--) | Meghatározza a polinomiális trendvonal rendjét. |
| [setOrder(byte value)](#setOrder-byte-) | Meghatározza a polinomiális trendvonal rendjét. |
| [getPeriod()](#getPeriod--) | Meghatározza a mozgóátlag trendvonal periódusát. |
| [setPeriod(byte value)](#setPeriod-byte-) | Meghatározza a mozgóátlag trendvonal periódusát. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (az egyenlettel egy címkén). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (az egyenlettel egy címkén). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A trendvonalhoz kapcsolódó jelmagyarázat bejegyzést képviseli. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding objektumot a "text" paraméterben megadott szöveggel. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tartalmazhat gazdag formázott szöveget. |
| [getTextFormat()](#getTextFormat--) | Visszaadja a szöveg formátumát. |
| [getChart()](#getChart--) | Visszaadja a szülő diagramot. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő bemutatóját. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

A trendvonal nevét adja vissza vagy állítja be. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

A trendvonal nevét adja vissza vagy állítja be. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

A trendvonal típusát adja vissza vagy állítja be. Olvasás/írás [TrendlineType](../../com.aspose.slides/trendlinetype).

**Visszatérési érték:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

A trendvonal típusát adja vissza vagy állítja be. Olvasás/írás [TrendlineType](../../com.aspose.slides/trendlinetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A trendvonal formátumát képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

A trendvonal formátumát képviseli. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Meghatározza, hogy a trendvonal hány kategóriát (vagy egy egységet a szórt diagramon) nyújt ki a sorozat adatainak előtt. Szórt és nem szórt diagramokon az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Visszatérési érték:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Meghatározza, hogy a trendvonal hány kategóriát (vagy egy egységet a szórt diagramon) nyújt ki a sorozat adatainak előtt. Szórt és nem szórt diagramokon az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Meghatározza, hogy a trendvonal hány kategóriát (vagy egységet a szórt diagramon) nyújt ki a sorozat adatainak után. Szórt és nem szórt diagramokon az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Visszatérési érték:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Meghatározza, hogy a trendvonal hány kategóriát (vagy egységet a szórt diagramon) nyújt ki a sorozat adatainak után. Szórt és nem szórt diagramokon az értéknek nem negatívnak kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Megadja azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Olvasás/írás double.

**Visszatérési érték:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Megadja azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak akkor támogatott, ha a trendvonal típusa exp, linear vagy poly. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (az Rsquaredvalue címkével együtt). Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (az Rsquaredvalue címkével együtt). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Meghatározza a polinomiális trendvonal rendjét. Más trendvonal típusoknál figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie. Olvasás/írás byte.

**Visszatérési érték:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Meghatározza a polinomiális trendvonal rendjét. Más trendvonal típusoknál figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Meghatározza a mozgóátlag trendvonal periódusát. Más trendvonal változatoknál figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie. Olvasás/írás byte.

**Visszatérési érték:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Meghatározza a mozgóátlag trendvonal periódusát. Más trendvonal változatoknál figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (az egyenlettel egy címkén). Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (az egyenlettel egy címkén). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

A trendvonalhoz kapcsolódó jelmagyarázat bejegyzést képviseli. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatérési érték:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializálja a TextFrameForOverriding objektumot a "text" paraméterben megadott szöveggel. Ha a TextFrameForOverriding már inicializálva van, egyszerűen megváltoztatja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Az új TextFrameForOverriding szövege. |

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveges érték felülírja a címke automatikusan generált szövegét. Az automatikusan generált címke szövege olyan szöveget jelent, amelyet a ShowSeriesName, ShowValue, ... tulajdonságok kezelnek, és a TextFormatManager.TextFormat tulajdonsággal formáznak. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatérési érték:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Visszaadja a szöveg formátumát. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatérési érték:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő diagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatérési érték:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő bemutatóját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)