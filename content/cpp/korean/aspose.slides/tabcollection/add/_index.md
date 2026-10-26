---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에 탭을 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides/tabcollection/add/
---
## TabCollection::Add(double, TabAlignment) 메서드


컬렉션에 [Tab](../../tab/)를 추가합니다.

```cpp
System::SharedPtr<ITab> Aspose::Slides::TabCollection::Add(double position, TabAlignment align) override
```


### 반환값

추가된 탭.

## TabCollection::Add(System::SharedPtr\<ITab\>) 메서드


컬렉션에 [Tab](../../tab/)를 추가합니다.

```cpp
int32_t Aspose::Slides::TabCollection::Add(System::SharedPtr<ITab> value) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ITab](../../itab/)\> | 컬렉션 끝에 추가될 [Tab](../../tab/) 객체입니다. |

### 반환값

탭이 추가된 인덱스입니다.

## 참고

* Enum [TabAlignment](../../tabalignment/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITab](../../itab/)
* 클래스 [TabCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)