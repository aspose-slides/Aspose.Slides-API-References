---
title: set_NumberGroupSizes()
second_title: Aspose.Slides for C++ API リファレンス
description: グループごとの桁数を設定します。
type: docs
weight: 495
url: /ja/system.globalization/numberformatinfo/set_numbergroupsizes/
---
## NumberFormatInfo::set_NumberGroupSizes(const ArrayPtr\<int\>\&) メソッド

グループごとの桁数を設定します。

```cpp
void System::Globalization::NumberFormatInfo::set_NumberGroupSizes(const ArrayPtr<int> &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [ArrayPtr](../../../system/arrayptr/)\<int\>\& | [Array](../../../system/array/) グループあたりの桁数（左から右へ）。各要素は1から9でなければならず、最後の要素は0にすることができ、これは「すべて結合」を意味します。最後の要素は繰り返されます。 |

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [NumberFormatInfo](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)