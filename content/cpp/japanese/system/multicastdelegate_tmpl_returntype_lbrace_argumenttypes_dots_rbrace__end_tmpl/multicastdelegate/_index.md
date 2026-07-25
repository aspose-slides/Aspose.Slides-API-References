---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API リファレンス
description: 空のコレクションを構築します。
type: docs
weight: 1
url: /ja/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() メソッド


空のコレクションを構築します。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) メソッド


デフォルトコンストラクタと同等です。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) メソッド


デリゲートコレクションの浅いコピーを実行します。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | const MulticastDelegate\& | デリゲートのコレクションをコピーする元となる MulticastDelegate クラスのインスタンス。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) メソッド


ムーブコンストラクタ。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | MulticastDelegate\&& | デリゲートのコレクションをムーブする元となる MulticastDelegate クラスのインスタンス。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) メソッド


インスタンスを構築し、指定されたデリゲートをデリゲートコレクションに追加します。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | デリゲートコレクションに追加するデリゲート |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) メソッド


インスタンスを構築し、指定された値をデリゲートコレクションに追加します。

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 新しく構築されたインスタンスのデリゲートコレクションに追加する値の型。型は Callback 型に変換可能である必要があります。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg | T | デリゲートコレクションに追加する値 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) メソッド


インスタンスを構築し、指定された値をデリゲートコレクションに追加します。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | デリゲートコレクションに追加する値 |

## 参照

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)