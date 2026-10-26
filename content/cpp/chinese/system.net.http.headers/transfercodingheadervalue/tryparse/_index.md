---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 TransferCodingHeaderValue 类的实例。
type: docs
weight: 92
url: /zh/system.net.http.headers/transfercodingheadervalue/tryparse/
---
## TransferCodingHeaderValue::TryParse(String, System::SharedPtr\<TransferCodingHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [TransferCodingHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::TransferCodingHeaderValue::TryParse(String input, System::SharedPtr<TransferCodingHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[TransferCodingHeaderValue](../)\>\& | 将分配已解析对象的实例。 |

### 返回值

解析成功时返回 true，否则返回 false。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [TransferCodingHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)