---
title: GetFormat()
second_title: Aspose.Slides for C++ API 參考
description: 取得特定類型的格式化器。
type: docs
weight: 742
url: /zh-hant/system.globalization/numberformatinfo/getformat/
---
## NumberFormatInfo::GetFormat(const TypeInfo\&) 方法


取得指定類型的格式化器。

```cpp
SharedPtr<Object> System::Globalization::NumberFormatInfo::GetFormat(const TypeInfo &format_type) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | 取得的格式化器類型；僅支援 [NumberFormatInfo](../) 類型。 |

### 回傳值

Formatter 或在不可用時返回 null。

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [TypeInfo](../../../system/typeinfo/)
* 類別 [NumberFormatInfo](../)
* 命名空間 [System::Globalization](../../)
* 函式庫 [Aspose.Slides](../../../)