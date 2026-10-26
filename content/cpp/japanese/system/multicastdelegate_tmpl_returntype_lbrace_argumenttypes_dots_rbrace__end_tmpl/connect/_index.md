---
title: connect()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデリゲートをコレクションに追加します。
type: docs
weight: 144
url: /ja/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) メソッド

指定されたデリゲートをコレクションに追加します。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [Callback](../callback/) | コレクションに追加するデリゲート |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) メソッド

指定された関数オブジェクトをデリゲートコレクションに追加します。関数オブジェクトは、コレクションに追加される前に Callback デリゲート型に変換されます。

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| R | コレクションに追加する関数オブジェクトの戻り値の型 |
| Args | コレクションに追加する関数オブジェクトの引数リスト |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| f | std::function\<R(Args...)> | コレクションに追加する関数オブジェクト |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) メソッド

指定された MulticastDelegate オブジェクトをデリゲートコレクションに追加します。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | デリゲートコレクションに追加する MulticastDelegate クラスのインスタンス |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) メソッド

指定されたオブジェクトの指定された非静的メソッドをデリゲートコレクションに追加します。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| MemberType | デリゲートコレクションに追加される非静的メソッドの型 |
| ClassType | デリゲートに追加されるオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定されたオブジェクトの非静的メソッドへのポインタ |
| obj | ClassType * | デリゲートコレクションに追加されるオブジェクトのメンバーメソッドへのポインタ |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) メソッド

指定されたオブジェクトの指定された非静的メソッドをデリゲートコレクションに追加します。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| MemberType | デリゲートコレクションに追加される非静的メソッドの型 |
| ClassType | デリゲートコレクションに追加されるオブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定されたオブジェクトの非静的メソッドへのポインタ |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | デリゲートコレクションに追加されるオブジェクトのメンバーメソッドへの共有ポインタ |

### 戻り値

自身への参照

## 参照

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* メソッド [MulticastDelegate](../multicastdelegate/)
* クラス [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)