---
title: ConstrainedCopy()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたソースから開始して、System.Array から要素の範囲をコピーします。
type: docs
weight: 716
url: /ja/system/array/constrainedcopy/
---
## Array::ConstrainedCopy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) メソッド

指定されたソースから開始する[System.Array](../)から要素の範囲をコピーします。

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::ConstrainedCopy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### テンプレート パラメータ

| パラメーター | 説明 |
| --- | --- |
| SrcType | Type of elements in source array |
| DstType | Type of elements in destination array |

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | ソース配列 |
| srcIndex | **int64_t** | [Index](../../index/)は、ソース配列内でコピーする項目の範囲の開始位置を示すインデックスです。 |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | 宛先配列 |
| dstIndex | **int64_t** | [Index](../../index/)は、コピーされた項目の挿入を開始する宛先配列内のインデックスです。 |
| count | **int64_t** | コピーする要素の数 |

## 備考

未完成の一時的な実装です！

## 参照

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [Array](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)