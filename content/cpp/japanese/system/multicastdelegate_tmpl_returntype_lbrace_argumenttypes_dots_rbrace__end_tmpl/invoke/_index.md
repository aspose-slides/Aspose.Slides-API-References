---
title: invoke()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在デリゲートコレクションに存在するすべてのデリゲートを呼び出します。デリゲートはコレクションに追加された順序で呼び出されます。このメソッドはデリゲートが実行されている間ブロックされます。
type: docs
weight: 222
url: /ja/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const メソッド

現在デリゲートコレクションに存在するすべてのデリゲートを呼び出します。デリゲートはコレクションに追加された順序で呼び出されます。このメソッドはデリゲートの実行中はブロックされます。

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | ArgumentTypes... | デリゲートに渡す引数 |

### 戻り値

最後に呼び出されたデリゲートの戻り値

## 参照

* クラス [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)