---
title: IActualLayout
second_title: Aspose.Slides pro Java API Reference
description: Určuje skutečnou polohu prvku grafu.
type: docs
url: /cs/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Určuje skutečnou polohu prvku grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getActualX()](#getActualX--) | Určuje skutečnou x-souřadnici (levý okraj) prvku grafu vzhledem k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečný horní okraj prvku grafu vzhledem k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku prvku grafu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku prvku grafu. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


Určuje skutečnou x-souřadnici (levý okraj) prvku grafu vzhledem k levému hornímu rohu grafu. Zavolejte metodu IChart.ValidateChartLayout() před tím, abyste získali skutečné hodnoty. Čte float.

**Návratová hodnota:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


Určuje skutečný horní okraj prvku grafu vzhledem k levému hornímu rohu grafu. Zavolejte metodu IChart.ValidateChartLayout() před tím, abyste získali skutečné hodnoty. Čte float.

**Návratová hodnota:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


Určuje skutečnou šířku prvku grafu. Zavolejte metodu IChart.ValidateChartLayout() před tím, abyste získali skutečné hodnoty. Čte float.

**Návratová hodnota:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


Určuje skutečnou výšku prvku grafu. Zavolejte metodu IChart.ValidateChartLayout() před tím, abyste získali skutečné hodnoty. Čte float.

**Návratová hodnota:**
float