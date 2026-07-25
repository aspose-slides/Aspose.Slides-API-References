---
title: MakeScopeGuard()
second_title: Aspose.Slides for C++ API リファレンス
description: ScopedGuard クラスのインスタンスを作成するファクトリ関数です。
type: docs
weight: 2809
url: /ja/system/makescopeguard/
---
## System::MakeScopeGuard(F) 関数

ScopedGuard クラスのインスタンスを作成するファクトリ関数。

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| The | 構成された ScopedGuard オブジェクトによって呼び出される関数オブジェクトの型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| f | F | ScopedGuard クラスのコンストラクタに渡す関数オブジェクト。 |

### 戻り値

ScopedGuard クラスの新しいインスタンス

## 参照

* 構造体 [ScopeGuard](../scopeguard/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)