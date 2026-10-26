---
title: CreatePortion()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 텍스트 부분을 생성합니다.
type: docs
weight: 1
url: /ko/aspose.slides/iportionfactory/createportion/
---
## IPortionFactory::CreatePortion() 메서드


빈 텍스트 부분을 생성합니다.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion()=0
```


### 반환 값

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::String) 메서드


지정된 문자열에서 텍스트 부분을 생성합니다.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::String str)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### 반환 값

[Portion](../../portion/).

## IPortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) 메서드


지정된 부분 데이터를 사용하여 부분을 생성합니다.

```cpp
virtual System::SharedPtr<IPortion> Aspose::Slides::IPortionFactory::CreatePortion(System::SharedPtr<IPortion> portion)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 사용할 부분. |

### 반환 값

[Portion](../../portion/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortion](../../iportion/)
* 클래스 [IPortionFactory](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)