---
title: SafeInvoke()
second_title: Aspose.Slides for C++ API リファレンス
description: ‘?.’ 演算子の実装。
type: docs
weight: 2653
url: /ja/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) 関数

‘?.’ 演算子の実装。

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| T0 | 式の型。 |
| T1 | ‘WhenTrue’ 式をカプセル化するラムダの型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| expr | T0\&& | 式の値。 |
| func | T1\&& | ファンクタにバインドされた ‘WhenTrue’ 式。 |

### 戻り値

expr の値が null でない場合、値を最初の引数として func を呼び出した結果を返し、そうでない場合は null を返します。

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)