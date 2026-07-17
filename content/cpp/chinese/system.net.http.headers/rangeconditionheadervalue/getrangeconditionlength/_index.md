---
title: GetRangeConditionLength()
second_title: Aspose.Slides for C++ API 参考
description: 将传入的字符串从指定索引转换为 RangeConditionHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/rangeconditionheadervalue/getrangeconditionlength/
---
## RangeConditionHeaderValue::GetRangeConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) 方法

将传入的字符串从指定索引转换为 [RangeConditionHeaderValue](../) 类的实例。

```cpp
static int32_t System::Net::Http::Headers::RangeConditionHeaderValue::GetRangeConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| startIndex | **int32_t** | 用于解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析后对象将被分配的实例。 |

### 返回值

返回已解析子字符串的长度；如果没有则返回 0。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [RangeConditionHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)