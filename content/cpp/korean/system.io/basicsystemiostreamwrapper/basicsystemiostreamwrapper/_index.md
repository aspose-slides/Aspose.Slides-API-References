---
title: BasicSystemIOStreamWrapper()
second_title: Aspose.Slides for C++ API 참조
description: BasicSystemIOStreamWrapper의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 생성자

새 인스턴스를 생성합니다 [BasicSystemIOStreamWrapper](../).

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 스트림에 대한 포인터 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 래핑 모드 |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) 생성자

복사 생성자. 삭제됨.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) 생성자

이동 생성자.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) 를 이동 |

## 참조

* 열거형 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../stream/)
* 클래스 [BasicSystemIOStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)