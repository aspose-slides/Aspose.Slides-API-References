---
title: CoalesceInternal()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 非NULL可能型に対する '??' 演算子の実装です。RT2 が RT1 に変換可能な場合のオーバーロードです。
type: docs
weight: 157
url: /ja/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) メソッド

非NULL可能型に対する '??' 演算子の実装です。RT2 が RT1 に変換可能な場合のオーバーロードです。

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T0 | LHS 値の型。 |
| T1 | RHS 式をカプセル化するラムダの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | RT1 | LHS 値。 |
| func | F | RHS 式。 |

### 戻り値

LHS 値が null でない場合、LHS を返し、そうでない場合は RHS 式を計算して結果を返します。

## 関連項目

* クラス [ObjectExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)