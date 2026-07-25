---
title: BuildObject()
second_title: Aspose.Slides for C++ API リファレンス
description: 共有所有権でオブジェクトを構築します。
type: docs
weight: 2250
url: /ja/system/buildobject/
---
## System::BuildObject(Args\&&...) 関数

共有所有権でオブジェクトを構築します。

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 構築するオブジェクトの型 |
| Args | オブジェクト構築のための引数型 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| args | Args\&&... | オブジェクトコンストラクタへ転送する引数 |

### 戻り値

共有ポインタ構築用に設定された ObjectBuilder

## 備考

[Object](../object/) の構築は [Get()](../get/) 呼び出しで完了しなければなりません

## 参照

* 型定義 [SharedPtr](../sharedptr/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)