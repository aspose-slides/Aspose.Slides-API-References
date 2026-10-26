---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 EntityTagHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/entitytagheadervalue/tryparse/
---
## EntityTagHeaderValue::TryParse(String, System::SharedPtr\<EntityTagHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [EntityTagHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::EntityTagHeaderValue::TryParse(String input, System::SharedPtr<EntityTagHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[EntityTagHeaderValue](../)\>\& | 将分配解析对象的实例。 |

### 返回值

解析成功时返回 true，否则返回 false。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [EntityTagHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)