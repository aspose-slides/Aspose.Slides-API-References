---
title: set_PercentGroupSizes()
second_title: Aspose.Slides の C++ API リファレンス
description: パーセント値のグループごとの桁数を設定します。
type: docs
weight: 625
url: /ja/system.globalization/numberformatinfo/set_percentgroupsizes/
---
## NumberFormatInfo::set_PercentGroupSizes(const ArrayPtr\<int\>\&) method


パーセント値のグループごとの桁数を設定します。

```cpp
void System::Globalization::NumberFormatInfo::set_PercentGroupSizes(const ArrayPtr<int> &value)
```


### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [ArrayPtr](../../../system/arrayptr/)\<int\>\& | [Array](../../../system/array/) グループあたりの桁数（左から右へ）。各要素は1から9である必要があり、最後の要素は0に設定でき、これは \"combine all\" を意味します。最後の要素は繰り返されます。 |

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [NumberFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)