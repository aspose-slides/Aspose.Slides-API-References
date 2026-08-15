---
title: TryGetValues()
second_title: Aspose.Slides for C++ API 參考文件
description: 嘗試根據指定的名稱取得對應的值。
type: docs
weight: 66
url: /zh-hant/system.net.http.headers/httpheaders/trygetvalues/
---
## HttpHeaders::TryGetValues(String, System::SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&) 方法

嘗試根據指定的名稱取得對應的值。

```cpp
bool System::Net::Http::Headers::HttpHeaders::TryGetValues(String name, System::SharedPtr<Collections::Generic::IEnumerable<String>> &values)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 標頭名稱。 |
| values | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | 將指派對應值的實例。 |

### 返回值

當找到指定名稱的標頭值時返回 true，否則返回 false。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 類別 [HttpHeaders](../)
* 命名空間 [System::Net::Http::Headers](../../)
* 函式庫 [Aspose.Slides](../../../)