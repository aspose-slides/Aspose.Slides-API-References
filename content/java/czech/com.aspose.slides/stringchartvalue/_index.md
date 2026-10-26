---
title: StringChartValue
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje řetězcovou hodnotu, kterou lze uložit v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem, 2) jako doslovná hodnota.
type: docs
url: /cs/com.aspose.slides/stringchartvalue/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseChartValue](../../com.aspose.slides/basechartvalue)

**Všechny implementované rozhraní:**
[com.aspose.slides.IStringChartValue](../../com.aspose.slides/istringchartvalue)
```
public class StringChartValue extends BaseChartValue implements IStringChartValue
```

Reprezentuje řetězcovou hodnotu, která může být uložena v dokumentu prezentace pptx dvěma způsoby: 1) v buňce/buňkách sešitu souvisejícího s grafem; 2) jako doslovná hodnota.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAsCells()](#getAsCells--) | Přiřazení nulové hodnoty není povoleno. |
| [setAsCells(IChartCellCollection value)](#setAsCells-com.aspose.slides.IChartCellCollection-) | Přiřazení nulové hodnoty není povoleno. |
| [getAsLiteralString()](#getAsLiteralString--) | Vrací nebo nastavuje hodnotu jako doslovný řetězec. |
| [setAsLiteralString(String value)](#setAsLiteralString-java.lang.String-) | Vrací nebo nastavuje hodnotu jako doslovný řetězec. |
| [getData()](#getData--) | Vrací nebo nastavuje objekt Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Vrací nebo nastavuje objekt Data. |
| [toString()](#toString--) | Vrací data řetězcové hodnoty. |
| [setFromOneCell(IChartDataCell cell)](#setFromOneCell-com.aspose.slides.IChartDataCell-) | Nastavuje hodnotu ze specifikované buňky. |
| [getCellsAddressInWorkbook()](#getCellsAddressInWorkbook--) | Pokud je vlastnost DataSourceType rovna DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. |

### getAsCells() {#getAsCells--}
```
public final IChartCellCollection getAsCells()
```

Přiřazení nulové hodnoty není povoleno. Vrácená hodnota je vždy nenulová. Čtení/zápis [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Vrací:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### setAsCells(IChartCellCollection value) {#setAsCells-com.aspose.slides.IChartCellCollection-}
```
public final void setAsCells(IChartCellCollection value)
```

Přiřazení nulové hodnoty není povoleno. Vrácená hodnota je vždy nenulová. Čtení/zápis [IChartCellCollection](../../com.aspose.slides/ichartcellcollection).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartCellCollection](../../com.aspose.slides/ichartcellcollection) |  |

### getAsLiteralString() {#getAsLiteralString--}
```
public final String getAsLiteralString()
```

Vrací nebo nastavuje hodnotu jako doslovný řetězec. Čtení/zápis String.

**Vrací:**
java.lang.String

### setAsLiteralString(String value) {#setAsLiteralString-java.lang.String-}
```
public final void setAsLiteralString(String value)
```

Vrací nebo nastavuje hodnotu jako doslovný řetězec. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public Object getData()
```

Vrací nebo nastavuje objekt Data. Čtení/zápis Object.

**Vrací:**
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public void setData(Object value)
```

Vrací nebo nastavuje objekt Data. Čtení/zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### toString() {#toString--}
```
public String toString()
```

Vrací data řetězcové hodnoty. Vrátí null, pokud je DataSourceType false a žádná řetězcová hodnota nebyla přiřazena.

**Vrací:**
java.lang.String

### setFromOneCell(IChartDataCell cell) {#setFromOneCell-com.aspose.slides.IChartDataCell-}
```
public final void setFromOneCell(IChartDataCell cell)
```

Nastavuje hodnotu ze specifikované buňky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| cell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell. |

### getCellsAddressInWorkbook() {#getCellsAddressInWorkbook--}
```
public final String getCellsAddressInWorkbook()
```

Pokud je vlastnost DataSourceType rovna DataSourceType.Worksheet, tato metoda vrací adresu buněk v sešitu, které představují řetězcová data. V opačném případě vrátí prázdný řetězec.

**Vrací:**
java.lang.String