---
title: GetCultureInfo()
second_title: Aspose.Slides for C++ API 參考文件
description: 依名稱取得文化。等同於 CreateSpecificCulture.
type: docs
weight: 586
url: /zh-hant/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) 方法

取得以名稱指定的文化。等同於 CreateSpecificCulture。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 預先定義的文化名稱或現有文化物件的名稱。 |

### 回傳值

新建立的文化物件。

## CultureInfo::GetCultureInfo(const String\&, const String\&) 方法

取得以名稱指定的文化。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | 文化名稱。 |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | 用於 [TextInfo](../../textinfo/) 與 [CompareInfo](../../compareinfo/) 物件的文化名稱。 |

### 回傳值

文化物件。

## CultureInfo::GetCultureInfo(int32_t) 方法

取得以 ID 指定的文化。

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| culture | **int32_t** | 文化識別碼。 |

### 回傳值

新建立的文化物件。

## 另請參閱

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* 類別 [String](../../../system/string/)
* 類別 [CultureInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)