---
title: BaseChartValue
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un valore di un grafico.
type: docs
url: /it/com.aspose.slides/basechartvalue/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

Rappresenta un valore di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | Specifica se la proprietà AsCell, AsCells, AsLiteralString o AsLiteralDouble è effettiva nei discendenti. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | Specifica se la proprietà AsCell, AsCells, AsLiteralString o AsLiteralDouble è effettiva nei discendenti. |
| [getData()](#getData--) | Dati. |
| [setData(Object value)](#setData-java.lang.Object-) | Dati. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Specifică se la proprietà AsCell, AsCells, AsLiteralString o AsLiteralDouble è effettiva nei discendenti. In altre parole specifica il tipo di valore della proprietà Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Per i punti in ChartDataPointCollection questa proprietà è sola lettura. In questo caso, per modificare il valore di questa proprietà è possibile utilizzare una delle proprietà ChartDataPointCollection.DataSourceTypeFor<...>.

**Restituisce:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

Specifică se la proprietà AsCell, AsCells, AsLiteralString o AsLiteralDouble è effettiva nei discendenti. In altre parole specifica il tipo di valore della proprietà Data. Lettura/scrittura [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

Per i punti in ChartDataPointCollection questa proprietà è sola lettura. In questo caso, per modificare il valore di questa proprietà è possibile utilizzare una delle proprietà ChartDataPointCollection.DataSourceTypeFor<...>.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Dati. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Dati. Lettura/scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject