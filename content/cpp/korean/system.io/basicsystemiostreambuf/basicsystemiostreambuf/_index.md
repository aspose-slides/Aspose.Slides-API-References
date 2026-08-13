---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: BasicSystemIOStreamBuf의 새 인스턴스를 생성합니다.
type: docs
weight: 14
url: /ko/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() 생성자

새 인스턴스를 생성합니다 [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) 생성자

새 인스턴스를 생성합니다 [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | 스트림에 대한 스마트 포인터 |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | 래핑 모드 |
| locale | const std::locale\& | [Stream](../../stream/)'s locale |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) 생성자

복사 생성자. 삭제되었습니다.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) 생성자

이동 생성자.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/)를 이동할 대상 |

## 참조

* 열거형 [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [BasicSystemIOStreamBuf](../)
* 클래스 [Stream](../../stream/)
* 네임스페이스 [System::IO](../../)
* 라이브러리 [Aspose.Slides](../../../)