---
title: disconnect()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデリゲートをデリゲート コレクションから削除します。
type: docs
weight: 170
url: /ja/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) メソッド

指定されたデリゲートをデリゲート コレクションから削除します。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| callback | [Callback](../callback/) | コレクションから削除するデリゲート |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) メソッド

指定されたオブジェクトの指定された非静的メソッドをデリゲート コレクションから削除します。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| MemberType | デリゲート コレクションから削除される非静的メソッドの型 |
| ClassType | デリゲート コレクションから削除されるオブジェクトのメソッドの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定されたオブジェクトの非静的メソッドへのポインタ |
| obj | ClassType * | デリゲート コレクションから削除されるオブジェクト メンバーメソッドへのポインタ |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) メソッド

指定されたオブジェクトの指定された非静的メソッドをデリゲート コレクションから削除します。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| MemberType | デリゲート コレクションから削除される非静的メソッドの型 |
| ClassType | デリゲート コレクションから削除されるオブジェクトのメソッドの型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定されたオブジェクトの非静的メソッドへのポインタ |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | デリゲート コレクションから削除されるオブジェクト メンバーメソッドへの共有ポインタ |

### 戻り値

自身への参照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) メソッド

指定された MulticastDelegate オブジェクトをデリゲート コレクションから削除します。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | デリゲート コレクションから削除する MulticastDelegate クラスのインスタンス |

### 戻り値

自身への参照

## 参照

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)