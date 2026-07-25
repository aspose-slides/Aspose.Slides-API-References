---
title: CoalesceAssign()
second_title: Aspose.Slides for C++ API リファレンス
description: '??=' 演算子の翻訳の実装。
type: docs
weight: 183
url: /ja/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) メソッド


'??=' 演算子の翻訳の実装。

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T0 | LHS の値の型。 |
| T1 | RHS 式をカプセル化するラムダの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | T0\& | LHS の値。 |
| func | T1 | RHS 式。 |

### 戻り値

LHS の値が null でない場合は LHS を返し、そうでない場合は RHS 式を計算して結果を返します。

## 参照

* クラス [ObjectExt](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)