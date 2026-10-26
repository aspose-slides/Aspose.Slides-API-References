---
title: IBaseChartValue
second_title: Aspose.Slides for Android via Java API Reference
description: チャートの値を表します。
type: docs
url: /ja/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

チャートの値を表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | AsCell または AsLiteralString または AsLiteralDouble プロパティが実際であるかどうかを指定します。 |
| [setDataSourceType(int value)](#setDataSourceType-int-) | AsCell または AsLiteralString または AsLiteralDouble プロパティが実際であるかどうかを指定します。 |
| [getData()](#getData--) | 読み取り/書き込み Object. |
| [setData(Object value)](#setData-java.lang.Object-) | 読み取り/書き込み Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

AsCell または AsLiteralString または AsLiteralDouble プロパティが実際であるかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。このプロパティは読み取り専用です。このプロパティの値を変更するには、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**戻り値:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

AsCell または AsLiteralString または AsLiteralDouble プロパティが実際であるかどうかを指定します。言い換えれば、Data プロパティの値の型を指定します。このプロパティは読み取り専用です。このプロパティの値を変更するには、ChartDataPointCollection.DataSourceTypeFor<...> プロパティのいずれかを使用できます。読み取り/書き込み [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int))。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

読み取り/書き込み Object.

**戻り値:**
java.lang.Object
### setData(java.lang.Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

読み取り/書き込み Object.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.Object |  |