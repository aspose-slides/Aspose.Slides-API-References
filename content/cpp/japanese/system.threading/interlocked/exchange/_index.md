---
title: Exchange()
second_title: Aspose.Slides for C++ API リファレンス
description: "変数の値を交換します。新しい値を格納し、格納する直前の変数の値を返します。"
type: docs
weight: 66
url: /ja/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) メソッド

変数の値を交換します。新しい値を格納し、格納する直前に変数が持っていた値を返します。

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 変数の型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location1 | T\& | 変更する変数への参照。 |
| value | T | 格納する値。 |

### 戻り値

変数が変更される直前の値。

## Interlocked::Exchange(T\&, T) メソッド

変数の値を交換します。新しい値を格納し、格納する直前に変数が持っていた値を返します。未実装です。

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T | 変数の型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location1 | T\& | 変更する変数への参照。 |
| value | T | 格納する値。 |

### 戻り値

変数が変更される直前の値。

## 関連項目

* クラス [Interlocked](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)