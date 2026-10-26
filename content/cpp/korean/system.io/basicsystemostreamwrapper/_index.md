---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides for C++ API 레퍼런스
description: "내부 버퍼로 BasicSystemIOStreamBuf를 사용한 std::ostream와 유사한 래퍼를 나타냅니다."
type: docs
weight: 79
url: /ko/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper 클래스

내부 버퍼로 [BasicSystemIOStreamBuf](../basicsystemiostreambuf/)를 사용한 std::ostream와 유사한 래퍼를 나타냅니다.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | move 생성자와 move 할당 연산자에서 포인터를 재설정하고 [swap()](./swap/)를 호출하는 데 사용됩니다. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | 새로운 [BasicSystemOStreamWrapper](./) 인스턴스를 생성합니다. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | 복사 생성자. 삭제되었습니다. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Move 생성자. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | 복사 할당 연산자. 삭제되었습니다. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Move 할당 연산자. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | *this과 **right**가 같지 않을 경우 swap을 호출합니다. |

## 타입 정의

| 타입정의 | 설명 |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## 참고

* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)