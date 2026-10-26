---
title: Compare()
second_title: Aspose.Slides for C++ API リファレンス
description: 二つの値を比較します。
type: docs
weight: 2731
url: /ja/system/compare/
---
## System::Compare(const TA\&, const TB\&) 関数

二つの値を比較します。

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TA | 最初の比較対象の型 |
| TB | 二番目の比較対象の型 |

### パラメータ

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const TA\& | 最初の比較対象 |
| b | const TB\& | 二番目の比較対象 |

### 戻り値

- 1 は **a** が **b** より小さい場合; 0 は値が等しい場合; 1 は **a** が **b** より大きい場合

## System::Compare(const TA\&, const TB\&) 関数

二つの浮動小数点値を比較します。

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| TA | 最初の比較対象の型 |
| TB | 二番目の比較対象の型 |

### パラメータ

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| a | const TA\& | 最初の比較対象 |
| b | const TB\& | 二番目の比較対象 |

### 戻り値

- 1 は **a** が **b** より小さい場合; 0 は値が等しい場合; 1 は **a** が **b** より大きい場合

## 関連項目

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)