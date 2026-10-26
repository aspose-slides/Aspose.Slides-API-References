---
title: DynamicWeakPtr()
second_title: Aspose.Slides for C++ API リファレンス
description: null スマートポインタを作成します。
type: docs
weight: 1
url: /ja/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) コンストラクタ


null スマートポインタを作成します。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) コンストラクタ


指定されたオブジェクトを指すスマートポインタを作成します。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | Pointee. |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) コンストラクタ


スマートポインタをコピー構築します。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | コピー元のポインティー情報を取得するスマートポインタ。 |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) コンストラクタ


スマートポインタをコピー構築します。

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | ソース ポインタのポインティー型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | コピー元のポインティー情報を取得するスマートポインタ。 |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) コンストラクタ


スマートポインタをコピー構築します。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | コピー元のポインティー情報を取得するスマートポインタ。 |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) コンストラクタ


スマートポインタをムーブ構築します。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | ムーブ元のポインティー情報を持つスマートポインタ。呼び出し後は使用できなくなります。 |

## 参照

* Typedef [Pointee_](../../smartptr/pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Typedef [DynamicWeakPtr_](../dynamicweakptr_/)
* Class [DynamicWeakPtr](../)
* Class [SmartPtr](../../smartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)