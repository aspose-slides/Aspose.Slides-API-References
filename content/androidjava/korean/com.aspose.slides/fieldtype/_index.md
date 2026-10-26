---
title: FieldType
second_title: Aspose.Slides for Android용 Java API 참조
description: 필드 유형을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/fieldtype/
---
**상속:**
java.lang.Object

**구현된 모든 인터페이스:**
[com.aspose.slides.IFieldType](../../com.aspose.slides/ifieldtype)
```
public final class FieldType implements IFieldType
```

필드는 필드 유형을 나타냅니다. 이 값은 필드가 업데이트될 때 필드 부분에 설정될 텍스트를 결정합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FieldType(String str)](#FieldType-java.lang.String-) | FieldType 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getInternalString()](#getInternalString--) | 이 FieldType 객체의 내부 이름을 반환합니다. |
| [setInternalString(String value)](#setInternalString-java.lang.String-) | 이 FieldType 객체의 내부 이름을 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 이 필드가 다른 필드와 같은지 확인합니다. |
| [hashCode()](#hashCode--) | 이 객체의 해시코드를 반환합니다. |
| [op_Equality(FieldType a, FieldType b)](#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 두 FieldType 객체가 같은지 확인합니다. |
| [op_Inequality(FieldType a, FieldType b)](#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-) | 두 FieldType 객체가 다른지 확인합니다. |
| [getSlideNumber()](#getSlideNumber--) | 현재 슬라이드 번호. |
| [getFooter()](#getFooter--) | 슬라이드 푸터. |
| [getHeader()](#getHeader--) | 슬라이드 헤더. |
| [getDateTime()](#getDateTime--) | 렌더링 애플리케이션의 기본 날짜/시간 형식으로 현재 날짜와 시간. |
| [getDateTime1()](#getDateTime1--) | 첫 번째 사전 정의된 형식(MM/DD/YYYY for english)으로 현재 날짜와 시간. |
| [getDateTime2()](#getDateTime2--) | 두 번째 사전 정의된 형식(Day, Month DD, YYYY for english)으로 현재 날짜와 시간. |
| [getDateTime3()](#getDateTime3--) | 세 번째 사전 정의된 형식(DD Month YYYY for english)으로 현재 날짜와 시간. |
| [getDateTime4()](#getDateTime4--) | 네 번째 사전 정의된 형식(Month DD, YYYY for english)으로 현재 날짜와 시간. |
| [getDateTime5()](#getDateTime5--) | 다섯 번째 사전 정의된 형식(DD-Mon-YY for english)으로 현재 날짜와 시간. |
| [getDateTime6()](#getDateTime6--) | 여섯 번째 사전 정의된 형식(Month YY for english)으로 현재 날짜와 시간. |
| [getDateTime7()](#getDateTime7--) | 일곱 번째 사전 정의된 형식(Mon-YY for english)으로 현재 날짜와 시간. |
| [getDateTime8()](#getDateTime8--) | 여덟 번째 사전 정의된 형식(MM/DD/YYYY hh:mm AM/PM for english)으로 현재 날짜와 시간. |
| [getDateTime9()](#getDateTime9--) | 아홉 번째 사전 정의된 형식(MM/DD/YYYY hh:mm:ss AM/PM for english)으로 현재 날짜와 시간. |
| [getDateTime10()](#getDateTime10--) | 열 번째 사전 정의된 형식(hh:mm for english)으로 현재 날짜와 시간. |
| [getDateTime11()](#getDateTime11--) | 열한 번째 사전 정의된 형식(hh:mm:ss for english)으로 현재 날짜와 시간. |
| [getDateTime12()](#getDateTime12--) | 열두 번째 사전 정의된 형식(hh:mm AM/PM for english)으로 현재 날짜와 시간. |
| [getDateTime13()](#getDateTime13--) | 열세 번째 사전 정의된 형식(hh:mm:ss AM/PM for english)으로 현재 날짜와 시간. |
### FieldType(String str) {#FieldType-java.lang.String-}
```
public FieldType(String str)
```

FieldType 클래스의 새 인스턴스를 초기화합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | java.lang.String |  |

### getInternalString() {#getInternalString--}
```
public final String getInternalString()
```

이 FieldType 객체의 내부 이름을 반환합니다. 읽기/쓰기 String.

**반환값:**
java.lang.String
### setInternalString(String value) {#setInternalString-java.lang.String-}
```
public final void setInternalString(String value)
```

이 FieldType 객체의 내부 이름을 반환합니다. 읽기/쓰기 String.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

이 필드가 다른 필드와 같은지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 비교할 필드. |

**반환값:**
boolean - 필드가 동일한 경우 True.
### hashCode() {#hashCode--}
```
public int hashCode()
```

이 객체의 해시코드를 반환합니다.

**반환값:**
int - 해시코드 int.
### op_Equality(FieldType a, FieldType b) {#op-Equality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Equality(FieldType a, FieldType b)
```

두 FieldType 객체가 같은지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 비교할 첫 번째 FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 비교할 두 번째 FieldType. |

**반환값:**
boolean - FieldType 객체가 같은 경우 True.
### op_Inequality(FieldType a, FieldType b) {#op-Inequality-com.aspose.slides.FieldType-com.aspose.slides.FieldType-}
```
public static boolean op_Inequality(FieldType a, FieldType b)
```

두 FieldType 객체가 다른지 확인합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | [FieldType](../../com.aspose.slides/fieldtype) | 비교할 첫 번째 FieldType. |
| b | [FieldType](../../com.aspose.slides/fieldtype) | 비교할 두 번째 FieldType. |

**반환값:**
boolean - FieldType 객체가 서로 다른 경우 True.
### getSlideNumber() {#getSlideNumber--}
```
public static FieldType getSlideNumber()
```

현재 슬라이드 번호. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getFooter() {#getFooter--}
```
public static FieldType getFooter()
```

슬라이드 푸터. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getHeader() {#getHeader--}
```
public static FieldType getHeader()
```

슬라이드 헤더. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime() {#getDateTime--}
```
public static FieldType getDateTime()
```

렌더링 애플리케이션의 기본 날짜/시간 형식으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime1() {#getDateTime1--}
```
public static FieldType getDateTime1()
```

첫 번째 사전 정의된 형식(MM/DD/YYYY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime2() {#getDateTime2--}
```
public static FieldType getDateTime2()
```

두 번째 사전 정의된 형식(Day, Month DD, YYYY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime3() {#getDateTime3--}
```
public static FieldType getDateTime3()
```

세 번째 사전 정의된 형식(DD Month YYYY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime4() {#getDateTime4--}
```
public static FieldType getDateTime4()
```

네 번째 사전 정의된 형식(Month DD, YYYY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime5() {#getDateTime5--}
```
public static FieldType getDateTime5()
```

다섯 번째 사전 정의된 형식(DD-Mon-YY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime6() {#getDateTime6--}
```
public static FieldType getDateTime6()
```

여섯 번째 사전 정의된 형식(Month YY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime7() {#getDateTime7--}
```
public static FieldName getDateTime7()
```

일곱 번째 사전 정의된 형식(Mon-YY for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime8() {#getDateTime8--}
```
public static FieldType getDateTime8()
```

여덟 번째 사전 정의된 형식(MM/DD/YYYY hh:mm AM/PM for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime9() {#getDateTime9--}
```
public static FieldType getDateTime9()
```

아홉 번째 사전 정의된 형식(MM/DD/YYYY hh:mm:ss AM/PM for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime10() {#getDateTime10--}
```
public static FieldType getDateTime10()
```

열 번째 사전 정의된 형식(hh:mm for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime11() {#getDateTime11--}
```
public static FieldType getDateTime11()
```

열한 번째 사전 정의된 형식(hh:mm:ss for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime12() {#getDateTime12--}
```
public static FieldType getDateTime12()
```

열두 번째 사전 정의된 형식(hh:mm AM/PM for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)
### getDateTime13() {#getDateTime13--}
```
public static FieldType getDateTime13()
```

열세 번째 사전 정의된 형식(hh:mm:ss AM/PM for english)으로 현재 날짜와 시간. 읽기 전용 [FieldType](../../com.aspose.slides/fieldtype).

**반환값:**
[FieldType](../../com.aspose.slides/fieldtype)