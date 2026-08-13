---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides for C++ API 레퍼런스
description: BasicSystemOStreamWrapper의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 생성자

[BasicSystemOStreamWrapper](../)의 새 인스턴스를 생성합니다.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 스트림에 대한 포인터 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 래핑 모드 |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) 생성자

복사 생성자. 삭제됨.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) 생성자

이동 생성자.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/)를 이동 |

## 관련 항목

* 열거형 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../stream/)
* 클래스 [BasicSystemOStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)