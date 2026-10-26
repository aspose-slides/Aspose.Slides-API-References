---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides for C++ API 참조
description: BasicSystemIStreamWrapper의 새 인스턴스를 생성합니다.
type: docs
weight: 1
url: /ko/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) 생성자

새 인스턴스를 생성합니다 [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | 스트림에 대한 포인터 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 래핑 모드 |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) 생성자

복사 생성자. 삭제됨.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) 생성자

이동 생성자.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) 이동될 |

## 참고

* 열거형 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../stream/)
* 클래스 [BasicSystemIStreamWrapper](../)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)