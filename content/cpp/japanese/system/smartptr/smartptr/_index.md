---
title: SmartPtr()
second_title: Aspose.Slides for C++ API リファレンス
description: 必要なモードの SmartPtr オブジェクトを作成します。
type: docs
weight: 1
url: /ja/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) コンストラクタ

必要なモードの [SmartPtr](../) オブジェクトを作成します。

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) コンストラクタ

必要なモードの null-pointer [SmartPtr](../) オブジェクトを作成します。

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mode | std::nullptr_t | ポインタモード。 |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) コンストラクタ

指定されたオブジェクトを指す [SmartPtr](../) を作成するか、生ポインタを [SmartPtr](../) に変換します。

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | ポインティー。 |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) コンストラクタ

[SmartPtr](../) オブジェクトをコピー構築します。両方のポインタはその後同じオブジェクトを指します。

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | コピー元のポインタ。 |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) コンストラクタ

[SmartPtr](../) オブジェクトをコピー構築します。両方のポインタはその後同じオブジェクトを指します。許可されていれば型変換も行います。

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Q | x が指すオブジェクトの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | コピー元のポインタ。 |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) コンストラクタ

[SmartPtr](../) オブジェクトをムーブ構築します。実質的に同じモードの 2 つのポインタを入れ替えます。呼び出し後、x は使用不能になる可能性があります。

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | ムーブするポインタ。 |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) コンストラクタ

異なる型の新しい配列を作成して参照配列の型を変換します。C# でサポートされていない配列型キャストを C++ で実装したい場合に便利です。

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | 元の配列の型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | コピー元配列へのポインタ（要素の型は異なります）。 |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |

## SmartPtr::SmartPtr(const Y\&) コンストラクタ

空の配列を初期化します。C# のコード構文を変換する際に使用されます。

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| Y | EmptyArrayInitializer 型のプレースホルダー。 |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) コンストラクタ

[SmartPtr](../) を構築します。このオブジェクトは ptr の所有情報を共有しますが、非関連かつ管理されていないポインタ p を保持します。

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | 所有権を共有する別のスマートポインタ。 |
| p | [Pointee_](../pointee_/) * | 管理対象オブジェクトへのポインタ。 |
| mode | [SmartPtrMode](../../smartptrmode/) | ポインタモード。 |
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// このクラスは印刷されるフィールドを含んでいます。
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// このクラスは Foo クラスのインスタンスを含んでいます。
class Bar : public System::Object
{
public:
  Foo data;
};

// Foo クラスのインスタンスから文字列を出力するために使用します。
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// オブジェクトを指す共有ポインタの数を出力します。
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // Bar クラスのインスタンスへの SharedPtr を作成します。
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // Bar クラスのインスタンスのフィールドを指す SharedPtr を作成します。
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // 'bar' ポインタを nullptr に設定します。
  bar.reset();
  PrintSharedCount(bar);
  // bar->data はまだ存在し、'foo' ポインタは有効です。
  PrintMessage(foo);

  return 0;
}
/*
このコード例は以下の出力を生成します:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## 参照

* 列挙体 [SmartPtrMode](../../smartptrmode/)
* 型定義 [Pointee_](../pointee_/)
* 型定義 [SmartPtr_](../smartptr_/)
* クラス [SmartPtr](../)
* クラス [Array](../../array/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)