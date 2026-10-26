---
title: AreFPNaN()
second_title: Aspose.Slides for C++ API リファレンス
description: 名前空間 詳細
type: docs
weight: 1
url: /ja/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) 関数

名前空間 [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | 最初の浮動小数点型。 |
| T2 | 2 番目の浮動小数点型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | T1 | 最初の浮動小数点値。 |
| rhs | T2 | 2 番目の浮動小数点値。 |

### 戻り値

両方の **lhs** と **rhs** が浮動小数点値である場合は true、そうでない場合は false です。

## 備考

2 つの浮動小数点値が両方とも NaN であることを確認します。非シグナリング NaN がサポートされている場合の状況を処理します。

## System::TestPredicates::AreFPNaN(T1, T2) 関数

2 つの浮動小数点値が両方とも NaN であることを確認します。非シグナリング NaN がサポートされていない場合の状況を処理します。

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| T1 | 最初の浮動小数点型。 |
| T2 | 2 番目の浮動小数点型。 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| lhs | T1 | 最初の浮動小数点値。 |
| rhs | T2 | 2 番目の浮動小数点値。 |

### 戻り値

NaN 値がサポートされていないため、常に false を返します。

## 関連項目

* 名前空間 [System::TestPredicates](../)
* ライブラリ [Aspose.Slides](../../)