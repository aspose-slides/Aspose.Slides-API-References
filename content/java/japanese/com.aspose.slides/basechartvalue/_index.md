---
title: BaseChartValue
second_title: Aspose.Slides for Java API リファレンス
description: チャートの値を表します。
type: docs
url: /ja/com.aspose.slides/basechartvalue/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject  
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

チャートの値を表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 子クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 子クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。 |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

子クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。読み書き [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

ChartDataPointCollection のポイントに対してこのプロパティは読み取り専用です。この場合、このプロパティの値を変更するには、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。

**戻り値:**  
int

### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

子クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。読み書き [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

ChartDataPointCollection のポイントに対してこのプロパティは読み取り専用です。この場合、このプロパティの値を変更するには、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. 読み書き Object。

**戻り値:**  
java.lang.Object

### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. 読み書き Object。

**パラメータ:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**  
com.aspose.slides.IDOMObject