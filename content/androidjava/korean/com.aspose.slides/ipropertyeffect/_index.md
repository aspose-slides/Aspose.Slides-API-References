---
title: IPropertyEffect
second_title: Java API를 통한 Android용 Aspose.Slides
description: 속성 효과 동작을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/ipropertyeffect/
---
**구현된 모든 인터페이스:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

속성 효과 동작을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFrom()](#getFrom--) | 애니메이션의 시작 값을 지정합니다. |
| [setFrom(String value)](#setFrom-java.lang.String-) | 애니메이션의 시작 값을 지정합니다. |
| [getTo()](#getTo--) | 애니메이션의 종료 값을 지정합니다. |
| [setTo(String value)](#setTo-java.lang.String-) | 애니메이션의 종료 값을 지정합니다. |
| [getBy()](#getBy--) | 애니메이션 시작 전 위치에 대한 상대 오프셋 값을 지정합니다. |
| [setBy(String value)](#setBy-java.lang.String-) | 애니메이션 시작 전 위치에 대한 상대 오프셋 값을 지정합니다. |
| [getValueType()](#getValueType--) | 속성 값의 유형을 지정합니다. |
| [setValueType(int value)](#setValueType-int-) | 속성 값의 유형을 지정합니다. |
| [getCalcMode()](#getCalcMode--) | 애니메이션의 보간 모드를 지정합니다. 읽기/쓰기 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | 애니메이션의 보간 모드를 지정합니다. 읽기/쓰기 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | 애니메이션의 포인트를 지정합니다. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | 애니메이션의 포인트를 지정합니다. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

애니메이션의 시작 값을 지정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

애니메이션의 시작 값을 지정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTo() {#getTo--}
```
public abstract String getTo()
```

애니메이션의 종료 값을 지정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

애니메이션의 종료 값을 지정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBy() {#getBy--}
```
public abstract String getBy()
```

애니메이션 시작 전 위치에 대한 상대 오프셋 값을 지정합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

애니메이션 시작 전 위치에 대한 상대 오프셋 값을 지정합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

속성 값의 유형을 지정합니다. 읽기/쓰기 [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**반환값:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

속성 값의 유형을 지정합니다. 읽기/쓰기 [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

애니메이션의 보간 모드를 지정합니다. 읽기/쓰기 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**반환값:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

애니메이션의 보간 모드를 지정합니다. 읽기/쓰기 [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

애니메이션의 포인트를 지정합니다. 읽기/쓰기 [IPointCollection](../../com.aspose.slides/ipointcollection).

**반환값:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

애니메이션의 포인트를 지정합니다. 읽기/쓰기 [IPointCollection](../../com.aspose.slides/ipointcollection).

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |