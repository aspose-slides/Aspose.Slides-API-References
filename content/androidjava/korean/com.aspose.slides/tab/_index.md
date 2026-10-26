---
title: Tab
second_title: Java API를 통한 Android용 Aspose.Slides 레퍼런스
description: 텍스트에 대한 탭 배열을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/tab/
---
**상속:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**구현된 모든 인터페이스:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

텍스트에 대한 탭 배열을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | 새 Tab을 생성합니다 |

## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | 탭의 위치를 반환하거나 설정합니다. |
| [setPosition(double value)](#setPosition-double-) | 탭의 위치를 반환하거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 탭의 정렬 스타일을 반환하거나 설정합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 탭의 정렬 스타일을 반환하거나 설정합니다. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 현재 인스턴스를 동일한 유형의 다른 객체와 비교합니다. |

### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```

새 Tab을 생성합니다

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | double | 탭 위치. |
| align | int | 정렬. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

버전. 읽기 전용 long.

**반환값:**
long

### getPosition() {#getPosition--}
```
public final double getPosition()
```

탭의 위치를 반환하거나 설정합니다. 이 속성을 할당하면 컬렉션에서 탭의 인덱스가 변경되고 Enumerator가 무효화될 수 있습니다. 읽기/쓰기 double.

**반환값:**
double

### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```

탭의 위치를 반환하거나 설정합니다. 이 속성을 할당하면 컬렉션에서 탭의 인덱스가 변경되고 Enumerator가 무효화될 수 있습니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

탭의 정렬 스타일을 반환하거나 설정합니다. 읽기/쓰기 [TabAlignment](../../com.aspose.slides/tabalignment).

**반환값:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

탭의 정렬 스타일을 반환하거나 설정합니다. 읽기/쓰기 [TabAlignment](../../com.aspose.slides/tabalignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```

현재 인스턴스를 동일한 유형의 다른 객체와 비교합니다.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 이 인스턴스와 비교할 객체. |

**반환값:**
int - 비교 대상들의 상대 순서를 나타내는 32비트 정수입니다. 반환값은 다음과 같은 의미를 가집니다:

 * < 0 - 이 인스턴스는 obj보다 작습니다.
 * = 0 - 이 인스턴스는 obj와 같습니다.
 * > 0 - 이 인스턴스는 obj보다 큽니다.