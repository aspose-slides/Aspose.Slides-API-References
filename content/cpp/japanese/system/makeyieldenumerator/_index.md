---
title: MakeYieldEnumerator()
second_title: Aspose.Slides for C++ API リファレンス
description: yield 関数から IEnumerator を作成します。
type: docs
weight: 2432
url: /ja/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) function


yield 関数から IEnumerator を作成します。

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | シーケンス内の要素の型 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | 実行する yield 関数 |

### Return Value

IEnumerator への共有ポインタ

## See Also

* 型定義 [SharedPtr](../sharedptr/)
* クラス [IEnumerator](../../system.collections.generic/ienumerator/)
* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)