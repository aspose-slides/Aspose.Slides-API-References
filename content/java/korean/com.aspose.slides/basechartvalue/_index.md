---
title: BaseChartValue
second_title: Aspose.Slides for Java API 레퍼런스
description: 차트의 값을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/basechartvalue/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IBaseChartValue](../../com.aspose.slides/ibasechartvalue), com.aspose.slides.IDOMObject
```
public abstract class BaseChartValue implements IBaseChartValue, IDOMObject
```

차트의 값을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDataSourceType()](#getDataSourceType--) | 자손에서 AsCell, AsCells, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [setDataSourceType(int value)](#setDataSourceType-int-) | 자손에서 AsCell, AsCells, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. |
| [getData()](#getData--) | Data. |
| [setData(Object value)](#setData-java.lang.Object-) | Data. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

자손에서 AsCell, AsCells, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection의 포인트에 대해 이 속성은 읽기 전용입니다. 이 경우 이 속성의 값을 변경하려면 ChartDataPointCollection.DataSourceTypeFor<...> 속성 중 하나를 사용할 수 있습니다.

**반환값:**
int
### setDataSourceType(int value) {#setDataSourceType-int-}
```
public final void setDataSourceType(int value)
```

자손에서 AsCell, AsCells, AsLiteralString 또는 AsLiteralDouble 속성이 실제인지 지정합니다. 다시 말해 Data 속성의 값 유형을 지정합니다. 읽기/쓰기 [DataSourceType](../../com.aspose.slides/datasourcetype).

--------------------

ChartDataPointCollection의 포인트에 대해 이 속성은 읽기 전용입니다. 이 경우 이 속성의 값을 변경하려면 ChartDataPointCollection.DataSourceTypeFor<...> 속성 중 하나를 사용할 수 있습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public abstract Object getData()
```

Data. 읽기/쓰기 Object.

**반환값:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public abstract void setData(Object value)
```

Data. 읽기/쓰기 Object.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.Object |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate 객체를 반환합니다. 읽기 전용 IDOMObject.

**반환값:**
com.aspose.slides.IDOMObject