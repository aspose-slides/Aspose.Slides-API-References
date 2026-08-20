---
title: ITab
second_title: Aspose.Slides for Java API 레퍼런스
description: 텍스트에 대한 탭을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/itab/
---
**구현된 모든 인터페이스:**
java.lang.Comparable
```
public interface ITab extends Comparable
```

텍스트에 대한 탭을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPosition()](#getPosition--) | 탭의 위치를 반환하거나 설정합니다. |
| [setPosition(double value)](#setPosition-double-) | 탭의 위치를 반환하거나 설정합니다. |
| [getAlignment()](#getAlignment--) | 탭의 정렬 스타일을 반환하거나 설정합니다. |
| [setAlignment(int value)](#setAlignment-int-) | 탭의 정렬 스타일을 반환하거나 설정합니다. |
### getPosition() {#getPosition--}
```
public abstract double getPosition()
```

탭의 위치를 반환하거나 설정합니다. 이 속성을 할당하면 컬렉션에서 탭의 인덱스가 변경되고 열거자를 무효화할 수 있습니다. 읽기/쓰기 double.

**반환:**
double
### setPosition(double value) {#setPosition-double-}
```
public abstract void setPosition(double value)
```

탭의 위치를 반환하거나 설정합니다. 이 속성을 할당하면 컬렉션에서 탭의 인덱스가 변경되고 열거자를 무효화할 수 있습니다. 읽기/쓰기 double.

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | double |  |
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

탭의 정렬 스타일을 반환하거나 설정합니다. 읽기/쓰기 [TabAlignment](../../com.aspose.slides/tabalignment).

**반환:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

탭의 정렬 스타일을 반환하거나 설정합니다. 읽기/쓰기 [TabAlignment](../../com.aspose.slides/tabalignment).

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | int |  |