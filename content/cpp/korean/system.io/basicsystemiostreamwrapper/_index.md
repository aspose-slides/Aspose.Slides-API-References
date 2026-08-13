---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides for C++ API 레퍼런스
description: "BasicSystemIOStreamBuf를 내부 버퍼로 사용한 std::iostream와 유사한 래퍼를 나타냅니다."
type: docs
weight: 53
url: /ko/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper 클래스


std::iostream와 유사한 래퍼를 나타내며 내부 버퍼로 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/)를 사용합니다.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | move 생성자 및 move 할당 연산자에서 포인터를 재설정하고 [swap()](./swap/)를 호출하는 데 사용됩니다. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIOStreamWrapper](./)의 새로운 인스턴스를 생성합니다. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | 복사 생성자. 삭제됨. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | move 생성자. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | 복사 할당 연산자. 삭제됨. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | move 할당 연산자. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | *this와 **right**가 다를 경우 교환을 호출합니다. |
## 타입정의

| 타입정의 | 설명 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |
## 관련 항목

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)