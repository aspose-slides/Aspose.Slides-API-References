---
title: GetRetryConditionLength()
second_title: Aspose.Slides C++ API 参考
description: 将传入的字符串从指定索引转换为 RetryConditionHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/retryconditionheadervalue/getretryconditionlength/
---
## RetryConditionHeaderValue::GetRetryConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) 方法

将传入的字符串从指定索引转换为 [RetryConditionHeaderValue](../) 类的实例。

```cpp
static int32_t System::Net::Http::Headers::RetryConditionHeaderValue::GetRetryConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| startIndex | **int32_t** | 用于解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析后对象将被赋值的实例。 |

### 返回值

返回解析子串的长度，否则返回 0。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [RetryConditionHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)