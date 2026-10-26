---
title: HolderInitializer< T, false >
second_title: C++용 Aspose.Slides API 참조
description: T가 값 타입인 경우에 대한 HolderInitializer 특수화입니다. 사용 컨텍스트는 임시 객체에 대한 참조를 반환하도록 허용하며, 인스턴스가 호출자에 의해 복사될 것이 보장됩니다. 따라서 이 특수화는 스텁으로만 사용되며 아무 작업도 하지 않습니다.
type: docs
weight: 1652
url: /ko/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct

[HolderInitializer](../holderinitializer/) T가 값 타입인 경우에 대한 특수화입니다. 사용 컨텍스트는 임시 객체에 대한 참조를 반환하도록 허용하며, 인스턴스가 호출자에 의해 복사될 것이 보장됩니다. 따라서 이 특수화는 스텁으로만 사용되며 아무 작업도 하지 않습니다.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |

## 참고

* 네임스페이스 [System](../)
* Library [Aspose.Slides](../../)