---
title: set_NumberGroupSizes()
second_title: Aspose.Slides for C++ API 參考
description: 設定每組的位數。
type: docs
weight: 495
url: /zh-hant/system.globalization/numberformatinfo/set_numbergroupsizes/
---
## NumberFormatInfo::set_NumberGroupSizes(const ArrayPtr\<int\>\&) 方法

設定每組的位數。

```cpp
void System::Globalization::NumberFormatInfo::set_NumberGroupSizes(const ArrayPtr<int> &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [ArrayPtr](../../../system/arrayptr/)\<int\>\& | [Array](../../../system/array/) 的每組位數，從左到右；每個元素必須在 1 到 9 之間，最後一個可以是 0，表示「全部合併」；最後一個元素會重複。 |

## 參見

* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [NumberFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)