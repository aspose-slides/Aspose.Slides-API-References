---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 RangeHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/rangeheadervalue/tryparse/
---
## RangeHeaderValue::TryParse(String, System::SharedPtr\<RangeHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [RangeHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::RangeHeaderValue::TryParse(String input, System::SharedPtr<RangeHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeHeaderValue](../)\>\& | 将分配已解析对象的实例。 |

### 返回值

解析成功时返回 true，否则返回 false。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [RangeHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)