---
title: BaseChartValue
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: チャートの値を表します。
type: docs
url: /ja/com.aspose.slides/basechartvalue/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

チャートの値を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 後継クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 後継クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。 |
| [getData()](#getData--) | データ。 |
| [setData(Object value)](#setData-java.lang.Object-) | データ。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

後継クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

ChartDataPointCollection のポイントに対してこのプロパティは読み取り専用です。このプロパティの値を変更する場合は、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。

**戻り値:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

後継クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble プロパティが実際に使用されているかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)。

--------------------

ChartDataPointCollection のポイントに対してこのプロパティは読み取り専用です。このプロパティの値を変更する場合は、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

データ。 読み取り/書き込み Object。

**戻り値:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

データ。 読み取り/書き込み Object。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate オブジェクトを返します。 読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject