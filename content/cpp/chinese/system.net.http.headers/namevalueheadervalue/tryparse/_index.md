---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 NameValueHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) 方法


尝试将传入的字符串转换为 [NameValueHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | 分配已解析对象的实例。 |

### 返回值

如果解析成功则返回 true，否则返回 false。

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [NameValueHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)