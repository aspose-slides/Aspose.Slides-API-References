---
title: IActualLayout
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Určuje skutečnou pozici prvku grafu.
type: docs
url: /cs/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Určuje skutečnou pozici prvku grafu.
## Metody

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Určuje skutečnou polohu x (levý) prvku grafu vzhledem k levému hornímu rohu grafu. |
| [getActualY()](#getActualY--) | Určuje skutečnou horní část prvku grafu vzhledem k levému hornímu rohu grafu. |
| [getActualWidth()](#getActualWidth--) | Určuje skutečnou šířku prvku grafu. |
| [getActualHeight()](#getActualHeight--) | Určuje skutečnou výšku prvku grafu. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Určuje skutečnou polohu x (levý) prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Čte float.

**Vrací:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Určuje skutečnou horní část prvku grafu vzhledem k levému hornímu rohu grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Čte float.

**Vrací:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Určuje skutečnou šířku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Čte float.

**Vrací:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Určuje skutečnou výšku prvku grafu. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečné hodnoty. Čte float.

**Vrací:**
float