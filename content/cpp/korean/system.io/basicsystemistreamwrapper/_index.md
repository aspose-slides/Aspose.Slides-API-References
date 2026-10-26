---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides for C++ API 레퍼런스
description: "BasicSystemIOStreamBuf를 내부 버퍼로 사용한 std::istream과 유사한 래퍼를 나타냅니다."
type: docs
weight: 66
url: /ko/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper 클래스

std::istream와 같은 래퍼를 나타내며 내부 버퍼로 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/)를 사용합니다.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | 이동 생성자와 이동 할당 연산자에서 포인터를 재설정하고 [swap()](./swap/)를 호출하는 데 사용됩니다. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | [BasicSystemIStreamWrapper](./)의 새 인스턴스를 생성합니다. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | 복사 생성자. 삭제됨. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | 이동 생성자. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | 복사 할당 연산자. 삭제됨. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | 이동 할당 연산자. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | *this와 **right**가 다를 경우 교환을 수행합니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## 참조

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)