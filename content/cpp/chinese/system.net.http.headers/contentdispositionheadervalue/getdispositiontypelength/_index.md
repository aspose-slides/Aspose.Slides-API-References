---
title: GetDispositionTypeLength()
second_title: Aspose.Slides C++ API 参考
description: 将传入的字符串从指定索引转换为 ContentDispositionHeaderValue 类的实例。
type: docs
weight: 300
url: /zh/system.net.http.headers/contentdispositionheadervalue/getdispositiontypelength/
---
## ContentDispositionHeaderValue::GetDispositionTypeLength(String, int32_t, System::SharedPtr\<Object\>\&) method

将传入的字符串从指定索引转换为 [ContentDispositionHeaderValue](../) 类的实例。

```cpp
static int32_t System::Net::Http::Headers::ContentDispositionHeaderValue::GetDispositionTypeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析后对象将被赋值的实例。 |

### 返回值

已解析子字符串的长度；若无则为 0。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [ContentDispositionHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)