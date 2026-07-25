---
title: ScopeGuard
second_title: Aspose.Slides for C++ API リファレンス
description: クラスのインスタンスがスコープを抜けたときに、特定の関数オブジェクトを実行するサービスを提供するサービスクラスです。
type: docs
weight: 1886
url: /ja/system/scopeguard/
---
## ScopeGuard 構造体

クラスのインスタンスがスコープを抜ける際に、特定の関数オブジェクトを実行するサービスを提供するサービスクラスです。

```cpp
template<typename F>class ScopeGuard
```

### テンプレートパラメータ

| パラメータ | 説明 |
| --- | --- |
| F | ScopedGuard クラスのインスタンスによって呼び出される関数オブジェクトの型 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Disable](./disable/)() | ガードの呼び出しを無効にします。 |
| [ScopeGuard](./scopeguard/)(F) | 指定された関数オブジェクトを呼び出すように設定されたインスタンスを構築します。 |
| [~ScopeGuard](./~scopeguard/)() | コンストラクタに渡された関数オブジェクトを呼び出します。 |

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)