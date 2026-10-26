---
title: Size
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 임의의 단위로 너비와 높이 차원을 설명하는 클래스입니다.
type: docs
url: /ko/com.aspose.slides.android/size/
---
**Inheritance:**  
java.lang.Object  
```
public class Size
```

일부 임의의 단위로 너비와 높이 차원을 설명하는 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | 새로운 Size 인스턴스를 생성합니다. |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | Size의 너비를 가져옵니다. |
| [getHeight()](#getHeight--) | Size의 높이를 가져옵니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 Size가 다른 Size와 같은지 확인합니다. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | 형식 "WxH" 로 문자열로 표현된 Size를 반환합니다. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

새로운 Size 인스턴스를 생성합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| width | int | Size의 너비 |
| height | int | Size의 높이 |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Size의 너비를 가져옵니다.

**반환값:**  
int - 너비

### getHeight() {#getHeight--}
```
public int getHeight()
```

Size의 높이를 가져옵니다.

**반환값:**  
int - 높이

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

이 Size가 다른 Size와 같은지 확인합니다.

두 Size는 너비와 높이가 모두 동일할 때에만 동일합니다.

Size 객체는 다른 유형의 객체와는 절대 동일하지 않습니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**반환값:**  
boolean -  true  if the objects were equal,  false  otherwise

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

형식 "WxH" 로 문자열로 표현된 Size를 반환합니다.

**반환값:**  
java.lang.String - Size의 문자열 표현