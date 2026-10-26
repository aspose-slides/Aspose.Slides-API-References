---
title: IsDefined()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された値が列挙型 E のメンバーであるかどうかを判定します。
type: docs
weight: 27
url: /ja/system/enum/isdefined/
---
## Enum::IsDefined(E) メソッド

指定された値が列挙型 **E** のメンバーであるかどうかを判定します。

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | E | チェックする値 |

### 戻り値

True if **value** is a member of enumeration **E**, otherwise - false

## Enum::IsDefined(T) メソッド

指定された値が列挙型 **T** のメンバーであるかどうかを判定します。

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | T | チェックする値 |

### 戻り値

True if **value** is a member of enumeration **T**, otherwise - false

## Enum::IsDefined(const String\&) メソッド

指定された名前を持つ値が列挙型 **E** のメンバーに含まれているかどうかを判定します。

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| name | const [String](../../string/)\& | チェックする名前 |

### 戻り値

True if a member of enum **E** with the specified name exists.

## 参照

* Typedef [UnderlyingType](../underlyingtype/)
* Class [String](../../string/)
* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)