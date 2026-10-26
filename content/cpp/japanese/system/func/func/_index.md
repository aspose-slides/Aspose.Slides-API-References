---
title: Func()
second_title: Aspose.Slides for C++ APIリファレンス
description: null-Func を作成するデフォルトコンストラクタです。
type: docs
weight: 1
url: /ja/system/func/func/
---
## Func::Func() コンストラクタ

null-Func を作成するデフォルトコンストラクタです。

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) コンストラクタ

[Func](../) オブジェクトを構築し、値（実際のコールバックまたは nullptr のいずれか）を割り当てるコンストラクタです。

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 引数型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arg | T\&& | 引数。 |

## Func::Func(const Func\&) コンストラクタ

コピーコンストラクタ。

```cpp
System::Func<Args>::Func(const Func &func)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) からデータをコピーするための。 |

## Func::Func(Func\&&) コンストラクタ

ムーブコンストラクタ。

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) からデータを移動するための。 |

## 参照

* Class [Func](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)