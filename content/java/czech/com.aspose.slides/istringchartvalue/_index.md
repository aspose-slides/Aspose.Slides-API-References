---
title: IStringChartValue
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje hodnotu řetězce, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem, 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/istringchartvalue/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMultipleCellChartValue](../../com.aspose.slides/imultiplecellchartvalue)
```
public interface IStringChartValue extends IMultipleCellChartValue
```

Reprezentuje hodnotu řetězce, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsLiteralString()](#getAsLiteralString--) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. |
| [toString()](#toString--) | Vrací řetězcovou reprezentaci. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Nastavuje hodnotu z určené buňky. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Pokud je vlastnost DataSourceType nastavena na DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. |

### getAsLiteralString() {#getAsLiteralString--}
```
public abstract String getAsLiteralString()
```

Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. Číst/zapisovat String.

**Vrací:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public abstract void setAsLiteralString(String value)
```

Vrací nebo nastavuje doslovný řetězec, pokud je vlastnost DataSourceType nastavena na DataSourceType.StringLiterals. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public abstract String toString()
```

Vrací řetězcovou reprezentaci.

**Vrací:**
java.lang.String - Řetězcová reprezentace hodnoty String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setFromOneCell(IChartDataCell cell)
```

Nastavuje hodnotu z určené buňky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Buňka. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public abstract String getCellsAddressInWorkbook()
```

Pokud je vlastnost DataSourceType nastavena na DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. V opačném případě vrací prázdný řetězec.

**Vrací:**
java.lang.String - Řetězcová hodnota String