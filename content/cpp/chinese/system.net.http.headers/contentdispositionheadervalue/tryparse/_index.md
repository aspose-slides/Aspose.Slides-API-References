---
title: TryParse()
second_title: Aspose.Slides C++ API 参考
description: 尝试将传入的字符串转换为 ContentDispositionHeaderValue 类的实例。
type: docs
weight: 287
url: /zh/system.net.http.headers/contentdispositionheadervalue/tryparse/
---
## ContentDispositionHeaderValue::TryParse(String, System::SharedPtr\<ContentDispositionHeaderValue\>\&) 方法


尝试将传入的字符串转换为 [ContentDispositionHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::ContentDispositionHeaderValue::TryParse(String input, System::SharedPtr<ContentDispositionHeaderValue> &parsedValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentDispositionHeaderValue](../)\>\& | 解析后的对象将被分配到的实例。 |

### 返回值

解析成功完成时返回 true，否则返回 false。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ContentDispositionHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)