---
title: Exists()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された Array オブジェクトが、指定された述語の要件を満たす要素を含んでいるかどうかを判断します。
type: docs
weight: 781
url: /ja/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) method

指定された [Array](../) オブジェクトが、指定された述語の要件を満たす要素を含んでいるかどうかを判断します。

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | 要素を検索する配列 |
| match | std::function\<**bool**(T)> | 要件を定義し、要素がそれらを満たすかどうかをチェックする関数オブジェクト |

### 戻り値

**arr** が **match** で定義された要件を満たす要素を含む場合は True

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)