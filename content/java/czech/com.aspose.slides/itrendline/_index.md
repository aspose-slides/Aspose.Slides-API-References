---
title: ITrendline
second_title: Aspose.Slides pro Java API Reference
description: Třída představuje čáru trendu řady grafu
type: docs
url: /cs/com.aspose.slides/itrendline/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Třída představuje čáru trendu řady grafu
## Metody

| Metoda | Popis |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Získá nebo nastaví název trendové čáry. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Získá nebo nastaví název trendové čáry. |
| [getTrendlineType()](#getTrendlineType--) | Získá nebo nastaví typ trendové čáry. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Získá nebo nastaví typ trendové čáry. |
| [getFormat()](#getFormat--) | Představuje formát trendové čáry. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Představuje formát trendové čáry. |
| [getBackward()](#getBackward--) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje před data řady, která je sledována. |
| [setBackward(double value)](#setBackward-double-) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje před data řady, která je sledována. |
| [getForward()](#getForward--) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje po datech řady, která je sledována. |
| [setForward(double value)](#setForward-double-) | Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje po datech řady, která je sledována. |
| [getIntercept()](#getIntercept--) | Určuje hodnotu, kde má trendová čára protínat osu y. |
| [setIntercept(double value)](#setIntercept-double-) | Určuje hodnotu, kde má trendová čára protínat osu y. |
| [getDisplayEquation()](#getDisplayEquation--) | Určuje, že rovnice trendové čáry je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Určuje, že rovnice trendové čáry je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [getOrder()](#getOrder--) | Určuje řád polynomické trendové čáry. |
| [setOrder(byte value)](#setOrder-byte-) | Určuje řád polynomické trendové čáry. |
| [getPeriod()](#getPeriod--) | Určuje periodu trendové čáry pro klouzavý průměr. |
| [setPeriod(byte value)](#setPeriod-byte-) | Určuje periodu trendové čáry pro klouzavý průměr. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Představuje položku legendy související s touto trendovou čárou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |

### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Získá nebo nastaví název trendové čáry. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Získá nebo nastaví název trendové čáry. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Získá nebo nastaví typ trendové čáry. Čtení/Zápis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Vrací:**
int

### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Získá nebo nastaví typ trendové čáry. Čtení/Zápis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Představuje formát trendové čáry. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)

### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Představuje formát trendové čáry. Čtení/Zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |

### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje před data řady, která je sledována. V rozptylových i nerostupových grafech musí být hodnota jakákoliv nezáporná hodnota. Čtení/Zápis double.

**Vrací:**
double

### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje před data řady, která je sledována. V rozptylových i nerostupových grafech musí být hodnota jakákoliv nezáporná hodnota. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getForward() {#getForward--}
```
public abstract double getForward()
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje po datech řady, která je sledována. V rozptylových i nerostupových grafech musí být hodnota jakákoliv nezáporná hodnota. Čtení/Zápis double.

**Vrací:**
double

### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Určuje počet kategorií (nebo jednotek v rozptylovém grafu), o které se trendová čára rozšiřuje po datech řady, která je sledována. V rozptylových i nerostupových grafech musí být hodnota jakákoliv nezáporná hodnota. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Určuje hodnotu, kde má trendová čára protínat osu y. Toto vlastnost je podporována pouze, když je typ trendové čáry exp, lineární nebo poly. Čtení/Zápis double.

**Vrací:**
double

### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Určuje hodnotu, kde má trendová čára protínat osu y. Toto vlastnost je podporována pouze, když je typ trendové čáry exp, lineární nebo poly. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Určuje, že rovnice trendové čáry je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/Zápis boolean.

**Vrací:**
boolean

### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Určuje, že rovnice trendové čáry je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Určuje řád polynomické trendové čáry. Pro ostatní typy trendových čar je ignorováno. Hodnota musí být mezi 2 a 6. Čtení/Zápis byte.

**Vrací:**
byte

### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Určuje řád polynomické trendové čáry. Pro ostatní typy trendových čar je ignorováno. Hodnota musí být mezi 2 a 6. Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Určuje periodu trendové čáry pro klouzavý průměr. Pro jiné varianty trendových čar je ignorováno. Hodnota musí být mezi 2 a 255. Čtení/Zápis byte.

**Vrací:**
byte

### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Určuje periodu trendové čáry pro klouzavý průměr. Pro jiné varianty trendových čar je ignorováno. Hodnota musí být mezi 2 a 255. Čtení/Zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/Zápis boolean.

**Vrací:**
boolean

### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Určuje, že hodnota R-squared trendové čáry je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Představuje položku legendy související s touto trendovou čárou Pouze pro čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)