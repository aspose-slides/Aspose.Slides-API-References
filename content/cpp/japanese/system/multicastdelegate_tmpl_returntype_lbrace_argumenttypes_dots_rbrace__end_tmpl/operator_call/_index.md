---
title: operator()()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在デリゲートコレクションに存在するすべてのデリゲートを呼び出します。デリゲートは、コレクションに追加された順序と同じ順序で実行されます。演算子はデリゲートが実行されている間ブロックされます。
type: docs
weight: 235
url: /ja/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const メソッド

現在コレクションに存在するすべてのデリゲートを呼び出します。デリゲートは、コレクションに追加された順序と同じ順序で呼び出されます。デリゲートの実行中は、この演算子はブロックされます。

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | ArgumentTypes... | 呼び出されるデリゲートに渡す引数 |

### 戻り値

最後に呼び出されたデリゲートの戻り値

## 参照

* クラス [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)