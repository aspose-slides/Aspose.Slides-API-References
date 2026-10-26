---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: Określa rzeczywistą pozycję elementu wykresu.
type: docs
url: /pl/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Określa rzeczywistą pozycję elementu wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getActualX()](#getActualX--) | Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. |
| [getActualY()](#getActualY--) | Określa rzeczywistą pozycję górną elementu wykresu względem lewego górnego rogu wykresu. |
| [getActualWidth()](#getActualWidth--) | Określa rzeczywistą szerokość elementu wykresu. |
| [getActualHeight()](#getActualHeight--) | Określa rzeczywistą wysokość elementu wykresu. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Określa rzeczywistą pozycję x (lewy) elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczytaj float.

**Zwraca:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Określa rzeczywistą pozycję górną elementu wykresu względem lewego górnego rogu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczytaj float.

**Zwraca:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Określa rzeczywistą szerokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczytaj float.

**Zwraca:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Określa rzeczywistą wysokość elementu wykresu. Wywołaj metodę IChart.ValidateChartLayout() przed, aby uzyskać rzeczywiste wartości. Odczytaj float.

**Zwraca:**
float