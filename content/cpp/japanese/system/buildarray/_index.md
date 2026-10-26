---
title: BuildArray()
second_title: Aspose.Slides for C++ API リファレンス
description: 配列を構築します。
type: docs
weight: 2276
url: /ja/system/buildarray/
---
## System::BuildArray() 関数


配列を構築します。

```cpp
template<typename T> Details::ObjectBuilder<Details::ArrayStorage<T>> System::BuildArray()
```


### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| T | 配列を構築する要素の型 |

### 戻り値

配列構築用に設定された ObjectBuilder

## 備考



ArrayPtr<T> を作成し、そのビルダーを返します
[Object](../object/) の構築は [Get()](../get/) 呼び出しで完了しなければなりません

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)