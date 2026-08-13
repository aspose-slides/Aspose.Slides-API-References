---
title: end()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컨테이너의 마지막 요소 다음에 위치하는 키-값 요소에 대한 KVPair-wrapper의 반복자를 반환합니다. C# 스타일로 구현되었으며, 반복자는 get_Key()와 get_Value() 인터페이스를 가진 KVPair 객체를 반환해야 합니다. 이 요소는 플레이스홀더 역할을 하며, 접근을 시도하면 정의되지 않은 동작이 발생합니다.
type: docs
weight: 235
url: /ko/system.collections.generic/basedictionary/end/
---
## BaseDictionary::end() const 메서드

컨테이너의 마지막 요소 다음에 오는 키-값 요소에 대한 KVPair-wrapper의 반복자를 반환합니다. C# 스타일로 구현되었으며 - 반복자는 get_Key()와 get_Value() 인터페이스를 갖는 KVPair-object를 반환해야 합니다. 이 요소는 플레이스홀더 역할을 하며, 접근하려고 시도하면 정의되지 않은 동작이 발생합니다.

```cpp
const_iterator System::Collections::Generic::BaseDictionary<Map>::end() const noexcept
```

### 반환값

컬렉션의 끝 요소 뒤에 배치된 가상의 요소를 가리키는 반복자입니다.

## 관련 항목

* 타입정의 [const_iterator](../const_iterator/)
* 클래스 [BaseDictionary](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)