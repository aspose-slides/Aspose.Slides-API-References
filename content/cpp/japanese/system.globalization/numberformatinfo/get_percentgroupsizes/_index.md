---
title: get_PercentGroupSizes()
second_title: Aspose.Slides for C++ API リファレンス
description: パーセンテージ値のグループごとの桁数を取得します。
type: docs
weight: 612
url: /ja/system.globalization/numberformatinfo/get_percentgroupsizes/
---
## NumberFormatInfo::get_PercentGroupSizes() const メソッド


パーセンテージ値のグループごとの桁数を取得します。

```cpp
ArrayPtr<int> System::Globalization::NumberFormatInfo::get_PercentGroupSizes() const
```


### 戻り値

[Array](../../../system/array/) は、左から右へ並べた各グループの桁数です。各要素は 1 から 9 の範囲で、最後の要素は 0 にでき、これは「すべて結合」を意味します。最後の要素は繰り返されます。

## 参照

* typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [NumberFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)