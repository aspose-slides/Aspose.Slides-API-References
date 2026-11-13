---
title: CachedChartValue
second_title: Aspose.Slides pro Java – Referenční dokumentace API
description: Reprezentuje uloženou hodnotu grafu, např. X, Y, velikost bubliny nebo hlavní hodnotu.
type: docs
url: /cs/com.aspose.slides/cachedchartvalue/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Reprezentuje uloženou hodnotu grafu (např. X, Y, velikost bubliny nebo hlavní hodnotu).
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [toString()](#toString--) | Vrací řetězcovou reprezentaci uložené hodnoty. |
| [toDouble()](#toDouble--) | Převádí uloženou hodnotu na double. |
| [getData()](#getData--) | Získává uložený datový objekt. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Vrací řetězcovou reprezentaci uložené hodnoty.

**Vrací:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Převádí uloženou hodnotu na double.

**Vrací:**
double - Číselná reprezentace nebo Double.NaN, pokud Data (\#getData.getData/\#setData(Object).setData(Object)) je null nebo nelze převést na double.
### getData() {#getData--}
```
public final Object getData()
```


Získává uložený datový objekt. Pouze ke čtení  Object .

**Vrací:**
java.lang.Object