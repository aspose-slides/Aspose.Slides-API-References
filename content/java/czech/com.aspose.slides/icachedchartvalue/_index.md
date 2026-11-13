---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Představuje uloženou hodnotu grafu, např. X, Y, velikost bubliny nebo hlavní hodnotu.
type: docs
url: /cs/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Představuje uloženou hodnotu grafu (např. X, Y, velikost bubliny nebo hlavní hodnotu).
## Metody

| Metoda | Popis |
| --- | --- |
| [getData()](#getData--) | Získá uložený datový objekt. |
| [toDouble()](#toDouble--) | Převede uloženou hodnotu na double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Získá uložený datový objekt. Pouze pro čtení  Object .

**Vrací:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Převede uloženou hodnotu na double.

**Vrací:**
double - číselná reprezentace, nebo Double.NaN pokud je Data (\#getData.getData) null nebo nelze převést na double.