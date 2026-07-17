---
title: TryParse()
second_title: Aspose.Slides C++ API 参考
description: 尝试将传入的字符串转换为 ContentRangeHeaderValue 类的实例。
type: docs
weight: 157
url: /zh/system.net.http.headers/contentrangeheadervalue/tryparse/
---
## ContentRangeHeaderValue::TryParse(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [ContentRangeHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::ContentRangeHeaderValue::TryParse(String input, System::SharedPtr<ContentRangeHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentRangeHeaderValue](../)\>\& | 将分配解析后对象的实例。 |

### 返回值

当解析成功完成时为 True，否则为 false。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ContentRangeHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)