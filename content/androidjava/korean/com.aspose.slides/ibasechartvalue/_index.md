---
title: IBaseChartValue
second_title: Aspose.Slides for Android Java API 레퍼런스
description: 차트 값을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ibasechartvalue/
---```
public interface IBaseChartValue
```

차트 값을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [getData()](#getData--) | 읽기/쓰기 Object. |
| [setData(Object value)](#setData-java.lang.Object-) | 읽기/쓰기 Object. |
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 Data 속성 값의 유형을 지정합니다. 이 속성은 읽기 전용입니다. 이 속성 값을 변경하려면 ChartDataPointCollection.DataSourceTypeFor<...> 속성 중 하나를 사용할 수 있습니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**반환:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public abstract void setDataSourceType(int value)
```

AsCell, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 Data 속성 값의 유형을 지정합니다. 이 속성은 읽기 전용입니다. 이 속성 값을 변경하려면 ChartDataPointCollection.DataSourceTypeFor<...> 속성 중 하나를 사용할 수 있습니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype)(\#getDataSourceType.getDataSourceType/\#setDataSourceType(int).setDataSourceType(int)).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

읽기/쓰기 Object.

**반환:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |