---
title: IStringChartValue
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje řetězcovou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícím s grafem; 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/istringchartvalue/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Reprezentuje řetězcovou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícím s grafem; 2) jako doslovná hodnota.
## Methods

| Method | Description |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavená na DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavená na DataSourceType.StringLiterals. |
| [toString()](#toString--) | Vrací řetězcovou reprezentaci. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Nastaví hodnotu z určené buňky. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Pokud je vlastnost DataSourceType nastavena na DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. |
### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```


Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavená na DataSourceType.StringLiterals. Čtení/Zápis String.

**Returns:**
java.lang.String
### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```


Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavená na DataSourceType.StringLiterals. Čtení/Zápis String.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```


Vrací řetězcovou reprezentaci.

**Returns:**
java.lang.String - Řetězcová reprezentace hodnoty String
### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```


Nastaví hodnotu z určené buňky.

**Parameters:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```


Pokud je vlastnost DataSourceType nastavena na DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. Jinak vrátí prázdný řetězec.

**Returns:**
java.lang.String - Řetězcová hodnota String