---
title: ITrendline
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Třída představuje trendovou linii řady grafu
type: docs
url: /cs/com.aspose.slides/itrendline/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

Třída představuje trendovou linii řady grafu
## Metody

| Metoda | Popis |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Získává nebo nastavuje název trendové linie. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Získává nebo nastavuje název trendové linie. |
| [getTrendlineType()](#getTrendlineType--) | Získává nebo nastavuje typ trendové linie. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Získává nebo nastavuje typ trendové linie. |
| [getFormat()](#getFormat--) | Představuje formát trendové linie. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Představuje formát trendové linie. |
| [getBackward()](#getBackward--) | Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje před data pro řadu, která je trendována. |
| [setBackward(double value)](#setBackward-double-) | Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje před data pro řadu, která je trendována. |
| [getForward()](#getForward--) | Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje po datech pro řadu, která je trendována. |
| [setForward(double value)](#setForward-double-) | Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje po datech pro řadu, která je trendována. |
| [getIntercept()](#getIntercept--) | Určuje hodnotu, kde má trendová linie protínat osu y. |
| [setIntercept(double value)](#setIntercept-double-) | Určuje hodnotu, kde má trendová linie protínat osu y. |
| [getDisplayEquation()](#getDisplayEquation--) | Určuje, že rovnice pro trendovou linii je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Určuje, že rovnice pro trendovou linii je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). |
| [getOrder()](#getOrder--) | Určuje řád polynomické trendové linie. |
| [setOrder(byte value)](#setOrder-byte-) | Určuje řád polynomické trendové linie. |
| [getPeriod()](#getPeriod--) | Určuje periodu trendové linie pro klouzavý průměr. |
| [setPeriod(byte value)](#setPeriod-byte-) | Určuje periodu trendové linie pro klouzavý průměr. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Určuje, že hodnota R-squared trendové linie je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Určuje, že hodnota R-squared trendové linie je zobrazena v grafu (ve stejném popisku jako rovnice). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Představuje položku legendy související s touto trendovou linií Pouze ke čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Získává nebo nastavuje název trendové linie. Čtení/zápis String.

**Vrací:**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Získává nebo nastavuje název trendové linie. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Získává nebo nastavuje typ trendové linie. Čtení/zápis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Vrací:**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Získává nebo nastavuje typ trendové linie. Čtení/zápis [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Představuje formát trendové linie. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Představuje formát trendové linie. Čtení/zápis [IFormat](../../com.aspose.slides/iformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje před data pro řadu, která je trendována. Na rozptylových a nerozptylových grafech může být hodnota jakákoli nezáporná hodnota. Čtení/zápis double.

**Vrací:**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje před data pro řadu, která je trendována. Na rozptylových a nerozptylových grafech může být hodnota jakákoli nezáporná hodnota. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje po datech pro řadu, která je trendována. Na rozptylových a nerozptylových grafech může být hodnota jakákoli nezáporná hodnota. Čtení/zápis double.

**Vrací:**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Určuje počet kategorií (nebo jednotek na rozptylovém grafu), o který se trendová linie rozšiřuje po datech pro řadu, která je trendována. Na rozptylových a nerozptylových grafech může být hodnota jakákoli nezáporná hodnota. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Určuje hodnotu, kde má trendová linie protínat osu y. Tato vlastnost je podporována pouze, když je typ trendové linie exp, linear nebo poly. Čtení/zápis double.

**Vrací:**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Určuje hodnotu, kde má trendová linie protínat osu y. Tato vlastnost je podporována pouze, když je typ trendové linie exp, linear nebo poly. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Určuje, že rovnice pro trendovou linii je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/zápis boolean.

**Vrací:**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Určuje, že rovnice pro trendovou linii je zobrazena v grafu (ve stejném popisku jako Rsquaredvalue). Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Určuje řád polynomické trendové linie. Pro jiné typy trendových linek je ignorováno. Hodnota musí být mezi 2 a 6. Čtení/zápis byte.

**Vrací:**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Určuje řád polynomické trendové linie. Pro jiné typy trendových linek je ignorováno. Hodnota musí být mezi 2 a 6. Čtení/zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Určuje periodu trendové linie pro klouzavý průměr. Pro jiné varianty trendových linek je ignorováno. Hodnota musí být mezi 2 a 255. Čtení/zápis byte.

**Vrací:**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Určuje periodu trendové linie pro klouzavý průměr. Pro jiné varianty trendových linek je ignorováno. Hodnota musí být mezi 2 a 255. Čtení/zápis byte.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Určuje, že hodnota R-squared trendové linie je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/zápis boolean.

**Vrací:**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Určuje, že hodnota R-squared trendové linie je zobrazena v grafu (ve stejném popisku jako rovnice). Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Představuje položku legendy související s touto trendovou linií Pouze ke čtení [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Vrací:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)