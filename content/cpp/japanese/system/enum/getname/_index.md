---
title: GetName()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値を持つ列挙定数の名前を返します。
type: docs
weight: 40
url: /ja/system/enum/getname/
---
## Enum::GetName(T) メソッド

指定された値を持つ列挙定数の名前を返します。

```cpp
template<class T> static std::enable_if<std::is_same<T, E>::value||std::is_convertible<T, UnderlyingType>::value, String>::type System::Enum<E, Guard>::GetName(T value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | 名前を取得する列挙定数の値 |

### 戻り値

指定された列挙定数の名前

## 参照

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)