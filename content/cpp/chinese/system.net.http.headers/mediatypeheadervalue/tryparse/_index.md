---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 MediaTypeHeaderValue 类的实例。
type: docs
weight: 131
url: /zh/system.net.http.headers/mediatypeheadervalue/tryparse/
---
## MediaTypeHeaderValue::TryParse(String, System::SharedPtr\<MediaTypeHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [MediaTypeHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::MediaTypeHeaderValue::TryParse(String input, System::SharedPtr<MediaTypeHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[MediaTypeHeaderValue](../)\>\& | 将分配已解析对象的实例。 |

### 返回值

解析成功时返回 true，否则返回 false。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [MediaTypeHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)