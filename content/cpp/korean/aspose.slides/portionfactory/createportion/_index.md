---
title: CreatePortion()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 빈 텍스트 구획을 생성합니다.
type: docs
weight: 1
url: /ko/aspose.slides/portionfactory/createportion/
---
## PortionFactory::CreatePortion() 메서드


빈 텍스트 구획을 생성합니다.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion() override
```


### 반환값

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::String) 메서드


지정된 문자열에서 텍스트 구획을 생성합니다.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::String str) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [System::String](../../../system/string/) | String. |

### 반환값

[Portion](../../portion/).

## PortionFactory::CreatePortion(System::SharedPtr\<IPortion\>) 메서드


지정된 구획 데이터를 사용하여 구획을 생성합니다.

```cpp
System::SharedPtr<IPortion> Aspose::Slides::PortionFactory::CreatePortion(System::SharedPtr<IPortion> portion) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../iportion/)\> | 사용할 구획. |

### 반환값

[Portion](../../portion/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortion](../../iportion/)
* 클래스 [PortionFactory](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)