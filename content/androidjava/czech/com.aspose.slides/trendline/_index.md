---
title: Trendline
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Třída představuje trendovou čáru řady grafu
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

Třída představuje trendovou čáru řady grafu
## Metody

| Metoda | Popis |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Získá nebo nastaví název trendové čáry. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Získá nebo nastaví název trendové čáry. |
| [getTrendlineType()](#getTrendlineType--) | Získá nebo nastaví typ trendové čáry. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Získá nebo nastaví typ trendové čáry. |
| [getFormat()](#getFormat--) | Představuje formát trendové čáry. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Představuje formát trendové čáry. |
| [getBackward()](#getBackward--) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje před data řady, která je trendována. |
| [setBackward(double value)](#setBackward-double-) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje před data řady, která je trendována. |
| [getForward()](#getForward--) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje po datech řady, která je trendována. |
| [setForward(double value)](#setForward-double-) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje po datech řady, která je trendována. |
| [getIntercept()](#getIntercept--) | Určuje hodnotu, kde trendová čára protne osu y. |
| [setIntercept(double value)](#setIntercept-double-) | Určuje hodnotu, kde trendová čára protne osu y. |
| [getDisplayEquation()](#getDisplayEquation--) | Určuje, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Určuje, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [getOrder()](#getOrder--) | Určuje řád polynomické trendové čáry. |
| [setOrder(byte value)](#setOrder-byte-) | Určuje řád polynomické trendové čáry. |
| [getPeriod()](#getPeriod--) | Určuje periodu trendové čáry pro klouzavý průměr. |
| [setPeriod(byte value)](#setPeriod-byte-) | Určuje periodu trendové čáry pro klouzavý průměr. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Představuje položku legendy související s touto trendovou čárou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [addTextFrameForOverriding(String text)](#addTextFrameForOverriding-java.lang.String-) | Inicializuje TextFrameForOverriding textem z parametru "text". |
| [getTextFrameForOverriding()](#getTextFrameForOverriding--) | Může obsahovat bohatě formátovaný text. |
| [getTextFormat()](#getTextFormat--) | Vrací formát textu. |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |
### getTrendlineName() {#getTrendlineName--}
```
public final String getTrendlineName()
```

Získá nebo nastaví název trendové čáry. Čtení/Zápis String.

**Vrací:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public final void setTrendlineName(String value)
```

Získá nebo nastaví název trendové čáry. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public final int getTrendlineType()
```

Získá nebo nastaví typ trendové čáry. Čtení/Zápis [TrendlineType](../../com.aspose.slides/trendlinetype).

**Vrací:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public final void setTrendlineType(int value)
```

Získá nebo nastaví typ trendové čáry. Čtení/Zápis [TrendlineType](../../com.aspose.slides/trendlinetype).

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

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje před data řady, která je trendována. U rozptylových i ne-rozptylových grafů může být hodnota libovolná nezáporná. Čtení/Zápis double.

**Vrací:**
double
### setBackward(double value) {#setBackward-double-}
```
public final void setBackward(double value)
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje před data řady, která je trendována. U rozptylových i ne-rozptylových grafů může být hodnota libovolná nezáporná. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public final double getForward()
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje po datech řady, která je trendována. U rozptylových i ne-rozptylových grafů může být hodnota libovolná nezáporná. Čtení/Zápis double.

**Vrací:**
double
### setForward(double value) {#setForward-double-}
```
public final void setForward(double value)
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které trendová čára zasahuje po datech řady, která je trendována. U rozptylových i ne-rozptylových grafů může být hodnota libovolná nezáporná. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public final double getIntercept()
```

Určuje hodnotu, kde trendová čára protne osu y. Tato vlastnost je podporována jen pro typy trendových čar exp, linear nebo poly. Čtení/Zápis double.

**Vrací:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public final void setIntercept(double value)
```

Určuje hodnotu, kde trendová čára protne osu y. Tato vlastnost je podporována jen pro typy trendových čar exp, linear nebo poly. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public final boolean getDisplayEquation()
```

Určuje, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public final void setDisplayEquation(boolean value)
```

Určuje, že rovnice pro trendovou čáru je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public final byte getOrder()
```

Určuje řád polynomické trendové čáry. Pro ostatní typy je ignorováno. Hodnota musí být mezi 2 a 6. Čtení/Zápis byte.

**Vrací:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public final void setOrder(byte value)
```

Určuje řád polynomické trendové čáry. Pro ostatní typy je ignorováno. Hodnota musí být mezi 2 a 6. Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public final byte getPeriod()
```

Určuje periodu trendové čáry pro klouzavý průměr. Pro ostatní varianty je ignorováno. Hodnota musí být mezi 2 a 255. Čtení/Zápis byte.

**Vrací:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public final void setPeriod(byte value)
```

Určuje periodu trendové čáry pro klouzavý průměr. Pro ostatní varianty je ignorováno. Hodnota musí být mezi 2 a 255. Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public final boolean getDisplayRSquaredValue()
```

Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/Zápis boolean.

**Vrací:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public final void setDisplayRSquaredValue(boolean value)
```

Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/Zápis boolean.

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

Inicializuje TextFrameForOverriding textem z parametru "text". Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text.

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

Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není null, pak tato formátovaná textová hodnota přepisuje automaticky generovaný text popisku dat. Automaticky generovaný text popisku dat znamená text řízený vlastnostmi ShowSeriesName, ShowValue, … a formátovaný vlastností TextFormatManager.TextFormat. Pouze pro čtení [ITextFrame](../../com.aspose.slides/itextframe).

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