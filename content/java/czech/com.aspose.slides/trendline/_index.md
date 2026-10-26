---
title: Trendline
second_title: Aspose.Slides pro Java API Reference
description: Třída představuje čáru trendu řady grafu
type: docs
url: /cs/com.aspose.slides/trendline/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ITrendline](../../com.aspose.slides/itrendline)
```
public class Trendline extends DomObject<TrendlineCollection> implements ITrendline
```

Třída představuje čáru trendu řady grafu
## Metody

| Metoda | Popis |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Získává nebo nastavuje název trendové čáry. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Získává nebo nastavuje název trendové čáry. |
| [getTrendlineType()](#getTrendlineType--) | Získává nebo nastavuje typ trendové čáry. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Získává nebo nastavuje typ trendové čáry. |
| [getFormat()](#getFormat--) | Představuje formát trendové čáry. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Představuje formát trendové čáry. |
| [getBackward()](#getBackward--) | Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které čára trendu pokračuje před daty pro řadu, která je trendována. |
| [setBackward(double value)](#setBackward-double-) | Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které čára trendu pokračuje před daty pro řadu, která je trendována. |
| [getForward()](#getForward--) | Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které trendová čára pokračuje po datech pro řadu, která je trendována. |
| [setForward(double value)](#setForward-double-) | Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které trendová čára pokračuje po datech pro řadu, která je trendována. |
| [getIntercept()](#getIntercept--) | Udává hodnotu, kde má trendová čára protínat osu y. |
| [setIntercept(double value)](#setIntercept-double-) | Udává hodnotu, kde má trendová čára protínat osu y. |
| [getDisplayEquation()](#getDisplayEquation--) | Udává, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Udává, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [getOrder()](#getOrder--) | Udává řád polynomické trendové čáry. |
| [setOrder(byte value)](#setOrder-byte-) | Udává řád polynomické trendové čáry. |
| [getPeriod()](#getPeriod--) | Udává periodu trendové čáry pro klouzavý průměr. |
| [setPeriod(byte value)](#setPeriod-byte-) | Udává periodu trendové čáry pro klouzavý průměr. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Udává, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Udává, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Představuje položku legendy související s touto trendovou čárou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializovat TextFrameForOverriding s textem v parametru "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Může obsahovat bohatě formátovaný text. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu. |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Získává nebo nastavuje název trendové čáry. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Získává nebo nastavuje název trendové čáry. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Získává nebo nastavuje typ trendové čáry. Čtení/Zápis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Vrací:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Získává nebo nastavuje typ trendové čáry. Čtení/Zápis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Představuje formát trendové čáry. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public final void setFormat(IFormat value)
```

Představuje formát trendové čáry. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public final double getBackward()
```

Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které čára trendu pokračuje před daty pro řadu, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Čtení/Zápis double.

**Vrací:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které čára trendu pokračuje před daty pro řadu, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public final double getForward()
```

Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které trendová čára pokračuje po datech pro řadu, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Čtení/Zápis double.

**Vrací:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Udává počet kategorií (nebo jednotek v rozptýleném grafu), o které trendová čára pokračuje po datech pro řadu, která je trendována. V rozptýlených i nerozptýlených grafech může být hodnota libovolná nezáporná hodnota. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Udává hodnotu, kde má trendová čára protínat osu y. Tato vlastnost je podporována pouze pro typy trendu exp, linear nebo poly. Čtení/Zápis double.

**Vrací:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Udává hodnotu, kde má trendová čára protínat osu y. Tato vlastnost je podporována pouze pro typy trendu exp, linear nebo poly. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Udává, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Udává, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Udává řád polynomické trendové čáry. Je ignorováno pro ostatní typy trendových čar. Hodnota musí být mezi 2 a 6. Čtení/Zápis byte.

**Vrací:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Udává řád polynomické trendové čáry. Je ignorováno pro ostatní typy trendových čar. Hodnota musí být mezi 2 a 6. Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Udává periodu trendové čáry pro klouzavý průměr. Je ignorováno pro ostatní varianty trendových čar. Hodnota musí být mezi 2 a 255. Čtení/Zápis byte.

**Vrací:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Udává periodu trendové čáry pro klouzavý průměr. Je ignorováno pro ostatní varianty trendových čar. Hodnota musí být mezi 2 a 255. Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Udává, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Udává, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Představuje položku legendy související s touto trendovou čárou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### addTextFrameForOverriding(String text) {#addTextFrameForOverriding-java.lang.String-}
```
public final ITextFrame addTextFrameForOverriding(String text)
```

Inicializovat TextFrameForOverriding s textem v parametru "text". Pokud je TextFrameForOverriding již inicializováno, pak jednoduše změní jeho text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text pro nový TextFrameForOverriding. |

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFrameForOverriding() {#getTextFrameForOverriding--}
```
public final ITextFrame getTextFrameForOverriding()
```

Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, pak tato formátovaná textová hodnota přepíše automaticky generovaný text popisku dat. Automaticky generovaný text popisku dat znamená text, který je řízen vlastnostmi ShowSeriesName, ShowValue, … a je formátován vlastností TextFormatManager.TextFormat. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

**Vrací:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Vrací formát textu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)