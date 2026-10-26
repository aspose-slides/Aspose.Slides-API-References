---
title: Create()
second_title: Aspose.Slides C++ API 參考
description: 建立特定文化的比較器。
type: docs
weight: 79
url: /zh-hant/system/stringcomparer/create/
---
## StringComparer::Create(const System::SharedPtr\<System::Globalization::CultureInfo\>\&, bool) 方法

建立特定文化的比較器。

```cpp
static StringComparerPtr System::StringComparer::Create(const System::SharedPtr<System::Globalization::CultureInfo> &culture, bool ignoreCase)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| culture | const [System::SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 要為其建立比較器的文化。 |
| ignoreCase | **bool** | 比較器是否應忽略大小寫。 |

### 返回值

指向新建立的比較器物件的指標。

## 參見

* Typedef [StringComparerPtr](../../stringcomparerptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [StringComparer](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)