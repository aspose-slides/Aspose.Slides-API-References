---
title: Delegate()
second_title: Aspose.Slides for C++ API リファレンス
description: デフォルトコンストラクタ。何も指し示さない delegate オブジェクトを構築します。
type: docs
weight: 1
url: /ja/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() メソッド

デフォルトコンストラクタ。何も指し示さない delegate オブジェクトを構築します。

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) メソッド




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```
## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) メソッド

ムーブ コピーコンストラクタ。指定された delegate が指すエンティティの所有権を取得します。

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | Delegate\&& | 指定された delegate から指されたエンティティを移動させる Delegate オブジェクト |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) メソッド

コンストラクタ。指定されたフリー関数または static メソッドへのポインタから delegate オブジェクトを構築します。

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| The | コンストラクタが引数として受け取る関数または static メソッドポインタの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| function | T | 新しく作成された Delegate インスタンスが指す関数または static メソッドへのポインタ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) メソッド

コンストラクタ。std::bind() によって生成された関数オブジェクトへの指定されたポインタから delegate を構築します。

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| The | コンストラクタが引数として受け取る std::bind() によって生成された関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| function | T | 新しく作成された Delegate インスタンスが指す "bind expression"（std::bind() によって生成された関数ポインタ）へのポインタ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) メソッド

コンストラクタ。指定された関数オブジェクトから delegate を構築します。

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コンストラクタが引数として受け取る関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functor_tag | int | ダミーの整数値; この引数は曖昧性を解消するために使用されます |
| functor | T\& | 新しく構築された delegate が指す関数オブジェクト |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) メソッド

ムーブコンストラクタ。指定された関数オブジェクトから delegate を構築します。

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T | コンストラクタが引数として受け取る関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| functor_tag | long | ダミーの整数値; この引数は曖昧性を解消するために使用されます |
| functor | T\&& | 新しく構築された delegate が指す関数オブジェクト |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) メソッド

コンストラクタ。指定されたオブジェクトの指定された非 static メンバメソッドを指す delegate を構築します。

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| MemberType | コンストラクタが引数として受け取る非 static メソッドの型 |
| ClassType | コンストラクタが引数として受け取るオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| member | MemberType ClassType::* | 新しく作成された delegate が指す非 static メソッドへのポインタ |
| obj | ClassType * | 新しく作成された delegate が指すオブジェクトメンバメソッドへのポインタ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) メソッド

コンストラクタ。指定されたオブジェクトの指定された非 static メンバメソッドを指す delegate を構築します。

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| MemberType | コンストラクタが引数として受け取る非 static メソッドの型 |
| ClassType | コンストラクタが引数として受け取るオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| member | MemberType MemberClass::* | 新しく作成された delegate が指す非 static メソッドへのポインタ |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 新しく作成された delegate が指すオブジェクトメンバメソッドへの shard ポインタ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) メソッド

std::function 関数オブジェクトを指す delegate オブジェクトを構築します。

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| R | コンストラクタが引数として受け取る関数オブジェクトの戻り値の型 |
| Args | コンストラクタが引数として受け取る関数オブジェクトの引数リスト |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| f | std::function\<R(Args...)> | 新しく作成された delegate オブジェクトが指す関数オブジェクト |

## 参照

* typedef [SharedPtr](../../sharedptr/)
* クラス [Delegate< ReturnType(ArgumentTypes...)>](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)