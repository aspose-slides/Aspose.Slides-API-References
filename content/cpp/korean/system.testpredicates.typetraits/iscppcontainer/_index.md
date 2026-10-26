---
title: IsCppContainer
second_title: Aspose.Slides for C++ API 레퍼런스
description: "특정 타입이 STL 스타일 컨테이너인지 확인합니다. 이를 위해 iterator 및 const_iterator 멤버 타입의 존재 여부를 확인합니다. 두 타입이 모두 존재하면 std::true_type를 상속하고, 그렇지 않으면 std::false_type를 상속합니다."
type: docs
weight: 40
url: /ko/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

특정 타입이 STL 스타일 컨테이너인지 확인합니다. 이를 위해 iterator 및 const_iterator 멤버 타입의 존재 여부를 확인합니다. 두 타입이 모두 존재하면 std::true_type를 상속하고, 그렇지 않으면 std::false_type를 상속합니다.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 확인할 타입. |
| Enable | SFINAE가 동작하도록 하는 형식 인자. |

## 참고

* 네임스페이스 [System::TestPredicates::TypeTraits](../)
* 라이브러리 [Aspose.Slides](../../)