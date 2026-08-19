---
title: DoubleChartValue
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje hodnotu typu double, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/doublechartvalue/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Všechny implementované rozhraní:**
[com.aspose.slides.IDoubleChartValue](../../com.aspose.slides/idoublechartvalue)
```
public class DoubleChartValue extends BaseChartValue implements IDoubleChartValue
```

Reprezentuje hodnotu typu double, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsCell()](#getAsCell--) | Vrací nebo nastavuje buňku dat grafu. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Vrací nebo nastavuje buňku dat grafu. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Vrací nebo nastavuje hodnotu jako doslovný double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Vrací nebo nastavuje hodnotu jako doslovný double. |
| [getData()](#getData--) | Vrací nebo nastavuje Data objekt. |
| [setData(Object value)](#setData-java.lang.Object-) | Vrací nebo nastavuje Data objekt. |
| [toDouble()](#toDouble--) | Převádí na double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Vrací nebo nastavuje buňku dat grafu. Čtení/zápis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Vrací nebo nastavuje buňku dat grafu. Čtení/zápis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```

Vrací nebo nastavuje hodnotu jako doslovný double. Čtení/zápis double.

**Vrací:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```

Vrací nebo nastavuje hodnotu jako doslovný double. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getData() {#getData--}
```
public Object getData()
```

Vrací nebo nastavuje Data objekt. Čtení/zápis Object.

**Vrací:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Vrací nebo nastavuje Data objekt. Čtení/zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |
### toDouble() {#toDouble--}
```
public final double toDouble()
```

Převádí na double.

**Vrací:**
double – Vrací LiteralDouble, pokud DataSourceType je roven DoubleLiterals. Pokud je DataSourceType roven Worksheet, vrací úspěšně převedenou hodnotu buňky na double, jinak vrací NaN.