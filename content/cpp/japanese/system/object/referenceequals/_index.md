---
title: ReferenceEquals()
second_title: Aspose.Slides for C++ API リファレンス
description: "文字列と nullptr の場合に対する Object::ReferenceEquals の特殊化。"
type: docs
weight: 261
url: /ja/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) メソッド

[Object::ReferenceEquals](./) の string と nullptr の場合の特殊化。

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) を nullptr と比較する。 |

### Return Value

文字列が null の場合は true、そうでない場合は false。

## Object::ReferenceEquals(String const\&, String const\&) メソッド

[Object::ReferenceEquals](./) の strings の場合の特殊化。

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | 比較する最初の string。 |
| str2 | [String](../../string/) const\& | 比較する二番目の string。 |

### Return Value

strings が一致する場合は true、そうでない場合は false。

## Object::ReferenceEquals(ptr const\&, ptr const\&) メソッド

オブジェクトを参照で比較します。

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | 比較する最初の ptr。 |
| objB | [ptr](../ptr/) const\& | 比較する二番目の ptr。 |

### Return Value

ポインタが一致すれば True、そうでなければ false。

## Object::ReferenceEquals(T const\&, T const\&) メソッド

オブジェクトを参照で比較します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T | 比較するオブジェクトの型。 |

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | T const\& | 比較する最初のオブジェクト。 |
| objB | T const\& | 比較する二番目のオブジェクト。 |

### Return Value

オブジェクトのアドレスが一致すれば True、そうでなければ false。

## Object::ReferenceEquals(T const\&, std::nullptr_t) メソッド

値型オブジェクトを nullptr と参照比較します。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Template parameters

| パラメータ | 説明 |
| --- | --- |
| T | 比較するオブジェクトの型。 |

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| objA | T const\& | 比較する最初のオブジェクト。 |

### Return Value

値型は null にできないため、常に false を返します。

## 参照

* Typedef [ptr](../ptr/)
* クラス [String](../../string/)
* クラス [Object](../)
* Struct [IsSmartPtr](../../issmartptr/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)