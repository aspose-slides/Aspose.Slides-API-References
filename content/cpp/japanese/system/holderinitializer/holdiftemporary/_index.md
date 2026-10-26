---
title: HoldIfTemporary()
second_title: Aspose.Slides for C++ API リファレンス
description: rvalue への参照を返します（const）
type: docs
weight: 14
url: /ja/system/holderinitializer/holdiftemporary/
---
## HolderInitializer::HoldIfTemporary(const T\&) メソッド

rvalueへの参照を返します（const）

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(const T &value)
```

## HolderInitializer::HoldIfTemporary(T\&) メソッド

rvalueへの参照を返します（非 const）

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &value)
```

## HolderInitializer::HoldIfTemporary(T\&&) メソッド

渡された lvalue をホルダーにコピーし、ホルダーの参照を返します。

```cpp
const T & System::HolderInitializer<T, R>::HoldIfTemporary(T &&value)
```

## 参照

* 構造体 [HolderInitializer](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)