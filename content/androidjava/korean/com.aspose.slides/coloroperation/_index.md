---
title: ColorOperation
second_title: Aspose.Slides for Android via Java API 레퍼런스
description: 색 변환에 사용되는 다양한 색상 작업을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/coloroperation/
---
**상속:**
java.lang.Object

**모든 구현된 인터페이스:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

색 변환에 사용되는 다양한 색상 작업을 나타냅니다. 불변 객체입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | 새 색 변환 작업을 생성합니다. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | 새 색 변환 작업을 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getOperationType()](#getOperationType--) | 작업의 유형을 반환하거나 설정합니다. |
| [getParameter()](#getParameter--) | 작업의 매개변수를 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 ColorOperation 인스턴스가 동일한지 여부를 결정합니다. |
| [hashCode()](#hashCode--) | 특정 유형에 대한 해시 함수 역할을 하며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에서 사용할 수 있습니다. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

새 색 변환 작업을 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| op | int | 작업 유형. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

새 색 변환 작업을 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| op | int | 작업 유형. |
| parameter | float | 작업 매개변수. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

작업의 유형을 반환하거나 설정합니다. 읽기 전용 [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**반환값:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

작업의 매개변수를 반환합니다. 읽기 전용 float.

**반환값:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

두 ColorOperation 인스턴스가 동일한지 여부를 결정합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 ColorOperation과 비교할 ColorOperation. |

**반환값:**
boolean - 지정된 ColorOperation이 현재 ColorOperation과 동일하면 **true**; 그렇지 않으면 **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

특정 유형에 대한 해시 함수 역할을 하며, 해시 알고리즘 및 해시 테이블과 같은 데이터 구조에서 사용할 수 있습니다.

**반환값:**
int