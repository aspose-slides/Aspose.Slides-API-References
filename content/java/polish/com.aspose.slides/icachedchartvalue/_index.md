---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje wartość wykresu w pamięci podręcznej, np. X, Y, rozmiar bąbelka lub wartość główną.
type: docs
url: /pl/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Reprezentuje wartość wykresu w pamięci podręcznej (np. X, Y, rozmiar bąbelka lub wartość główną).

## Metody

| Metoda | Opis |
| --- | --- |
| [getData()](#getData--) | Pobiera obiekt danych w pamięci podręcznej. |
| [toDouble()](#toDouble--) | Konwertuje wartość w pamięci podręcznej na typ double. |
### getData() {#getData--}
```
public abstract Object getData()
```

Pobiera obiekt danych w pamięci podręcznej. Tylko do odczytu  Object .

**Zwraca:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

Konwertuje wartość w pamięci podręcznej na typ double.

**Zwraca:**
double - Reprezentacja numeryczna lub Double.NaN, jeśli Data (\#getData.getData) jest nullem lub nie może zostać skonwertowana na typ double.