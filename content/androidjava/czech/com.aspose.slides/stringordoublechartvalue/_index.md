---
title: StringOrDoubleChartValue
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje řetězec nebo dvojitou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem, 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/stringordoublechartvalue/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IStringOrDoubleChartValue](../../com.aspose.slides/istringordoublechartvalue)
```
public class StringOrDoubleChartValue extends BaseChartValue implements IStringOrDoubleChartValue
```

Reprezentuje řetězec nebo dvojitou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsCell()](#getAsCell--) | Vrací nebo nastavuje buňku dat grafu. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Vrací nebo nastavuje buňku dat grafu. |
| [getAsLiteralString()](#getAsLiteralString--) | Vrací nebo nastavuje hodnotu jako doslovný řetězec. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Vrací nebo nastavuje hodnotu jako doslovný řetězec. |
| [getAsLiteralDouble()](#getAsLiteralDouble--) | Vrací nebo nastavuje hodnotu jako doslovné double. |
| [setAsLiteralDouble(double value)](#setAsLiteralDouble-double-) | Vrací nebo nastavuje hodnotu jako doslovné double. |
| [getData()](#getData--) | Vrací nebo nastavuje objekt Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Vrací nebo nastavuje objekt Data. |
| [toDouble()](#toDouble--) | Převádí na double. |
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Vrací nebo nastavuje buňku dat grafu. Číst/Zapisovat [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Vrací nebo nastavuje buňku dat grafu. Číst/Zapisovat [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```


Vrací nebo nastavuje hodnotu jako doslovný řetězec. Číst/Zapisovat String.

**Vrací:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```


Vrací nebo nastavuje hodnotu jako doslovný řetězec. Číst/Zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getAsLiteralDouble() {#getAsLiteralDouble--}
```
public final double getAsLiteralDouble()
```


Vrací nebo nastavuje hodnotu jako doslovné double. Číst/Zapisovat double.

**Vrací:**
double
### setAsLiteralDouble(double value) {#setAsLiteralDouble-double-}
```
public final void setAsLiteralDouble(double value)
```


Vrací nebo nastavuje hodnotu jako doslovné double. Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getData() {#getData--}
```
public Object getData()
```


Vrací nebo nastavuje objekt Data. Číst/Zapisovat Object.

**Vrací:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```


Vrací nebo nastavuje objekt Data. Číst/Zapisovat Object.

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
double - Double value.