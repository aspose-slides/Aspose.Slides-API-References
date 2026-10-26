---
title: operator=()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartPtr オブジェクトをムーブ代入します。x は使用できなくなります。
type: docs
weight: 27
url: /ja/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) メソッド

[SmartPtr](../) オブジェクトをムーブ代入します。x は使用できなくなります。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | ムーブ代入先のポインター。 |

### 戻り値

このオブジェクトへの参照です。

## SmartPtr::operator=(const SmartPtr_&) メソッド

[SmartPtr](../) オブジェクトをコピー代入します。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | コピー代入先のポインター。 |

### 戻り値

このオブジェクトへの参照です。

## SmartPtr::operator=(const SmartPtr\<Q\>\&) メソッド

[SmartPtr](../) オブジェクトをコピー代入します。必要な型変換を行います。

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| Q | x が指すオブジェクトの型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | コピー代入先のポインター。 |

### 戻り値

このオブジェクトへの参照です。

## SmartPtr::operator=(Pointee_ *) メソッド

[SmartPtr](../) オブジェクトに対して生ポインタを代入します。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | 代入するポインター値。 |

### 戻り値

このオブジェクトへの参照です。

## SmartPtr::operator=(std::nullptr_t) メソッド

ポインタの値を nullptr に設定します。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### 戻り値

このオブジェクトへの参照です。

## 参照

* Typedef [SmartPtr_](../smartptr_/)
* Typedef [Pointee_](../pointee_/)
* Class [SmartPtr](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)