---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API リファレンス
description: yield 関数から IEnumerable を作成します。
type: docs
weight: 2419
url: /ja/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) 関数

yield 関数から IEnumerable を作成します。

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### テンプレート パラメーター

| パラメーター | 説明 |
| --- | --- |
| T | シーケンス内の要素の型 |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | 実行する yield 関数 |

### 戻り値

IEnumerable への共有ポインタ

## 関連項目

* 型定義 [SharedPtr](../sharedptr/)
* クラス [IEnumerable](../../system.collections.generic/ienumerable/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)