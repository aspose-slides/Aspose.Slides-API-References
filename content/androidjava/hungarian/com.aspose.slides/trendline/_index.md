---
title: Trendline
second_title: Aspose.Slides for Android Java API referencia
description: Az osztály a diagram sorozat trendvonalát reprezentálja
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

Osztály a diagram sorozat trendvonalát reprezentálja
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Lekéri vagy beállítja a trendvonal nevét. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Lekéri vagy beállítja a trendvonal nevét. |
| [getTrendlineType()](#getTrendlineType--) | Lekéri vagy beállítja a trendvonal típusát. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Lekéri vagy beállítja a trendvonal típusát. |
| [getFormat()](#getFormat--) | A trendvonal formátumát reprezentálja. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | A trendvonal formátumát reprezentálja. |
| [getBackward()](#getBackward--) | Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai előtt kiterjeszt. |
| [setBackward(double value)](#setBackward-double-) | Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai előtt kiterjeszt. |
| [getForward()](#getForward--) | Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai után kiterjeszt. |
| [setForward(double value)](#setForward-double-) | Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai után kiterjeszt. |
| [getIntercept()](#getIntercept--) | Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt. |
| [setIntercept(double value)](#setIntercept-double-) | Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt. |
| [getDisplayEquation()](#getDisplayEquation--) | Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (ugyanazon címkén, ahol az R-négyzet érték szerepel). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (ugyanazon címkén, ahol az R-négyzet érték szerepel). |
| [getOrder()](#getOrder--) | Meghatározza a polinomiális trendvonal rendjét. |
| [setOrder(byte value)](#setOrder-byte-) | Meghatározza a polinomiális trendvonal rendjét. |
| [getPeriod()](#getPeriod--) | Meghatározza a trendvonal periódusát mozgó átlag trendvonal esetén. |
| [setPeriod(byte value)](#setPeriod-byte-) | Meghatározza a trendvonal periódusát mozgó átlag trendvonal esetén. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (ugyanazon címkén, mint az egyenlet). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (ugyanazon címkén, mint az egyenlet). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | A legend bejegyzést reprezentálja, amely ehhez a trendvonalhoz kapcsolódik. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializálja a TextFrameForOverriding-et a "text" paraméter szövegével. |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Tartalmazhat gazdag formázott szöveget. |
| [getTextFormat()](#getTextFormat--) | Visszatér a szöveg formátummal. |
| [getChart()](#getChart--) | Visszatér a szülő diagrammal. |
| [getSlide()](#getSlide--) | Visszatér a FillFormat szülő diájával. |
| [getPresentation()](#getPresentation--) | Visszatér a FillFormat szülő prezentációjával. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Lekéri vagy beállítja a trendvonal nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Lekéri vagy beállítja a trendvonal nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Lekéri vagy beállítja a trendvonal típusát. Olvasás/írás [TrendlineType](../../com.aspose.slides/trendlinetype).

**Visszatér:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Lekéri vagy beállítja a trendvonal típusát. Olvasás/írás [TrendlineType](../../com.aspose.slides/trendlinetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

A trendvonal formátumát reprezentálja. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Visszatér:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

A trendvonal formátumát reprezentálja. Olvasás/írás [IFormat](../../com.aspose.slides/iformat).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai előtt kiterjeszt. Szórt és nem szórt diagramok esetén az értéknek nemnegatívnak kell lennie. Olvasás/írás double.

**Visszatér:**
double

### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai előtt kiterjeszt. Szórt és nem szórt diagramok esetén az értéknek nemnegatívnak kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai után kiterjeszt. Szórt és nem szórt diagramok esetén az értéknek nemnegatívnak kell lennie. Olvasás/írás double.

**Visszatér:**
double

### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Meghatározza a kategóriák (vagy szórt diagramon mértékegységek) számát, amelyet a trendvonal a sorozat adatai után kiterjeszt. Szórt és nem szórt diagramok esetén az értéknek nemnegatívnak kell lennie. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak az exp, linear vagy poly típusú trendvonalaknál támogatott. Olvasás/írás double.

**Visszatér:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt. Ez a tulajdonság csak az exp, linear vagy poly típusú trendvonalaknál támogatott. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (ugyanazon címkén, ahol az R-négyzet érték szerepel). Olvasás/írás boolean.

**Visszatér:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Megadja, hogy a trendvonal egyenlete megjelenjen a diagramon (ugyanazon címkén, ahol az R-négyzet érték szerepel). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Meghatározza a polinomiális trendvonal rendjét. Más típusú trendvonalaknál figyelmen kívül marad. Az érték 2 és 6 között kell legyen. Olvasás/írás byte.

**Visszatér:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Meghatározza a polinomiális trendvonal rendjét. Más típusú trendvonalaknál figyelmen kívül marad. Az érték 2 és 6 között kell legyen. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Meghatározza a trendvonal periódusát mozgó átlag trendvonal esetén. Más trendvonal változatoknál figyelmen kívül marad. Az érték 2 és 255 között kell legyen. Olvasás/írás byte.

**Visszatér:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Meghatározza a trendvonal periódusát mozgó átlag trendvonal esetén. Más trendvonal változatoknál figyelmen kívül marad. Az érték 2 és 255 között kell legyen. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (ugyanazon címkén, mint az egyenlet). Olvasás/írás boolean.

**Visszatér:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Megadja, hogy a trendvonal R-négyzet értéke megjelenjen a diagramon (ugyanazon címkén, mint az egyenlet). Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

A legend bejegyzést reprezentálja, amely ehhez a trendvonalhoz kapcsolódik. Csak olvasható [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Visszatér:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializálja a TextFrameForOverriding-et a "text" paraméter szövegével. Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen módosítja a szövegét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Szöveg az új TextFrameForOverriding-hez. |

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem null, akkor ez a formázott szöveg felülírja az adatcímke automatikusan generált szövegét. Az automatikusan generált szöveg azt jelenti, hogy a ShowSeriesName, ShowValue, … tulajdonságok kezelik, és a TextFormatManager.TextFormat tulajdonsággal formázzák. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Visszatér a szöveg formátummal. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatér:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszatér a szülő diagrammal. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszatér a FillFormat szülő diájával. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszatér a FillFormat szülő prezentációjával. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)