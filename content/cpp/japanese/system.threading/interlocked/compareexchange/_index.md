---
title: CompareExchange()
second_title: Aspose.Slides for C++ API リファレンス
description: "変数の値を比較交換します：変数が特定の値と等しいかを確認し、格納された値が期待値と一致した場合にのみ新しい値を格納します。"
type: docs
weight: 79
url: /ja/system.threading/interlocked/compareexchange/
---
## Interlocked::CompareExchange(T\&, T, T) メソッド

変数の値を比較交換します：変数が特定の値と等しいかを確認し、格納された値が期待値と一致した場合にのみ新しい値を格納します。

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 変数の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location1 | T\& | 変更する変数への参照 |
| value | T | 格納する値 |
| comparand | T | 交換前に変数の値と比較する値 |

### 戻り値

操作開始時の変数の値。変更されたかどうかに関係なく返されます。

## Interlocked::CompareExchange(T\&, T, T) メソッド

変数の値を比較交換します：変数が特定の値と等しいかを確認し、格納された値が期待値と一致した場合にのみ新しい値を格納します。実装されていません。

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::CompareExchange(T &location1, T value, T comparand)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | 変数の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location1 | T\& | 変更する変数への参照 |
| value | T | 格納する値 |
| comparand | T | 交換前に変数の値と比較する値 |

### 戻り値

操作開始時の変数の値。変更されたかどうかに関係なく返されます。

## Interlocked::CompareExchange(int32_t\&, int32_t, int32_t, bool\&) メソッド

変数の値を比較交換します：変数が特定の値と等しいかを確認し、格納された値が期待値と一致した場合にのみ新しい値を格納します。

```cpp
static int32_t System::Threading::Interlocked::CompareExchange(int32_t &location1, int32_t value, int32_t comparand, bool &succeeded)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| location1 | **int32_t**\& | 変更する変数への参照 |
| value | **int32_t** | 格納する値 |
| comparand | **int32_t** | 交換前に変数の値と比較する値 |
| succeeded | **bool**\& | 交換が行われた場合は true に、そうでない場合は false に設定される変数への参照 |

### 戻り値

操作開始時の変数の値。変更されたかどうかに関係なく返されます。

## 参照

* クラス [Interlocked](../)
* 名前空間 [System::Threading](../../)
* ライブラリ [Aspose.Slides](../../../)