---
title: IsDBNull()
second_title: Aspose.Slides for C++ API リファレンス
description: 未実装です。
type: docs
weight: 14
url: /ja/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) メソッド

未実装。

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```

## Convert::IsDBNull(const SharedPtr\<T\>\&) メソッド

未実装 偽の実装で、値が nullptr かどうかをチェックします。

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 構造体 [Convert](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)