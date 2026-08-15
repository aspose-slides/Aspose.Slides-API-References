---
title: IsDefined()
second_title: Aspose.Slides for C++ API 參考文件
description: 未實作。指示是否已將指定類型或其衍生類型的一個或多個屬性套用於此成員。
type: docs
weight: 157
url: /zh-hant/system/typeinfo/isdefined/
---
## TypeInfo::IsDefined(const TypeInfo\&, bool) const 方法

未實作。指示是否已將指定類型或其衍生類型的一個或多個屬性套用於此成員。

```cpp
bool System::TypeInfo::IsDefined(const TypeInfo &attributeType, bool inherit) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | 要搜尋的自訂屬性類型。搜尋會包含衍生類型。 |
| inherit | **bool** | true 表示搜尋此成員的繼承鏈以尋找屬性；false 表示不搜尋。此參數對屬性和事件會被忽略。 |

### 返回值

true 表示已將 attributeType 或其任何衍生類型的一個或多個實例套用於此成員；false 表示未套用。

## 另請參閱

* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)