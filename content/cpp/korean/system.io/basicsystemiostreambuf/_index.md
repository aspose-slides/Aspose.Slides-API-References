---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides for C++ API 참조
description: "System::IO::Stream와 유사한 스트림을 래핑하고 std::iostream과 같은 스트림 내부 버퍼로 사용할 수 있도록 하는 버퍼를 나타냅니다."
type: docs
weight: 40
url: /ko/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf 클래스


[System::IO::Stream](../stream/)-와 유사한 스트림을 래핑하고 std::iostream과 같은 스트림 내부 버퍼로 사용할 수 있게 하는 버퍼를 나타냅니다.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | 이동 생성자 및 이동 할당 연산자에서 포인터를 재설정하고 [swap()](./swap/)를 호출하는 데 사용됩니다. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | 새로운 [BasicSystemIOStreamBuf](./) 인스턴스를 생성합니다. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | 새로운 [BasicSystemIOStreamBuf](./) 인스턴스를 생성합니다. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | 복사 생성자. 삭제됨. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | 이동 생성자. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | 복사 할당 연산자. 삭제됨. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | 이동 할당 연산자. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | *this와 right가 다를 경우 교환을 호출합니다. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | 소멸자. |
## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |
## 참고

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)