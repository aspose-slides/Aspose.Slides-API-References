---
title: SizeF
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 부동 소수점 값을 사용하는 임의 단위의 너비와 높이 차원을 설명하는 클래스입니다.
type: docs
url: /ko/com.aspose.slides.android/sizef/
---
**상속:**  
java.lang.Object  
```
public class SizeF
```

부동 소수점 값을 사용하는 임의 단위의 너비와 높이 차원을 설명하는 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | 새 SizeF 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 크기의 너비를 가져옵니다. |
| [getHeight()](#getHeight--) | 크기의 높이를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 크기가 다른 크기와 같은지 확인합니다. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | 형식 "WxH" 로 나타낸 문자열을 반환합니다. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```

새 SizeF 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| width | float | 크기의 너비 |
| height | float | 크기의 높이 |

### getWidth() {#getWidth--}
```
public float getWidth()
```

크기의 너비를 가져옵니다.

**반환값:**
float - 너비

### getHeight() {#getHeight--}
```
public float getHeight()
```

크기의 높이를 가져옵니다.

**반환값:**
float - 높이

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

이 크기가 다른 크기와 같은지 확인합니다.

두 크기는 너비와 높이가 모두 동일할 때에만 같다.

이를 위해 너비/높이 부동 소수점 값은 Float\#floatToIntBits(float).floatToIntBits(float) 메서드가 각각 적용될 때 동일한 int 값을 반환하는 경우에만 동일하다고 간주합니다.

**매개변수:**
| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**반환값:**
boolean - 객체가 동일하면 true, 그렇지 않으면 false

### hashCode() {#hashCode--}
```
public int hashCode()
```

**반환값:**
int

### toString() {#toString--}
```
public String toString()
```

형식 "WxH" 로 나타낸 문자열을 반환합니다.

**반환값:**
java.lang.String - 크기의 문자열 표현