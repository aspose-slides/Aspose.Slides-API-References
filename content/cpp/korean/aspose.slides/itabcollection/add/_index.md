---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 탭을 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides/itabcollection/add/
---
## ITabCollection::Add(double, TabAlignment) 메서드

컬렉션에 [Tab](../../tab/)를 추가합니다.

```cpp
virtual System::SharedPtr<ITab> Aspose::Slides::ITabCollection::Add(double position, TabAlignment align)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | **double** | [Tab](../../tab/) 위치. |
| align | [TabAlignment](../../tabalignment/) | [Tab](../../tab/) 정렬. |

### 반환값

추가된 탭.

## ITabCollection::Add(System::SharedPtr\<ITab\>) 메서드

컬렉션에 [Tab](../../tab/)를 추가합니다.

```cpp
virtual int32_t Aspose::Slides::ITabCollection::Add(System::SharedPtr<ITab> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | 컬렉션 끝에 추가될 [Tab](../../tab/) 객체. |

### 반환값

탭이 추가된 인덱스.

## 참고

* 열거형 [TabAlignment](../../tabalignment/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITab](../../itab/)
* 클래스 [ITabCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)