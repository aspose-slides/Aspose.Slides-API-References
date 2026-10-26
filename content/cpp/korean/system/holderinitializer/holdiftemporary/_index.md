---
title: HoldIfTemporary()
second_title: Aspose.Slides for C++ API 참조
description: rvalue에 대한 참조를 반환합니다 (const)
type: docs
weight: 14
url: /ko/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) 메서드


rvalue에 대한 참조를 반환합니다 (const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) 메서드


rvalue에 대한 참조를 반환합니다 (non-const)

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) 메서드


전달된 lvalue를 holder에 복사한 다음 holder 참조를 반환합니다.

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## 참조

* Struct [HolderInitializer](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)