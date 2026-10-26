---
title: IBaseChartValue
second_title: Aspose.Slides for Java API Reference
description: Represents a value of a chart.
type: docs
url: /ja/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

チャートの値を表します。

## メソッド

| Method | Description |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | このプロパティは AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | このプロパティは AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。 |
| [getData()](#getData--) | 読み書き可能な Object。 |
| [setData(Object value)](#setData-java.lang.Object-) | 読み書き可能な Object。 |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

このプロパティは AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、Data プロパティの値の型を指定します。このプロパティは読み取り専用です。このプロパティの値を変更するには、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。読み書き [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**戻り値:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

このプロパティは AsCell または AsLiteralString または AsLiteralDouble プロパティが実際に使用されているかを指定します。言い換えると、Data プロパティの値の型を指定します。このプロパティは読み取り専用です。このプロパティの値を変更するには、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。読み書き [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

読み書き可能な Object。

**戻り値:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

読み書き可能な Object。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |