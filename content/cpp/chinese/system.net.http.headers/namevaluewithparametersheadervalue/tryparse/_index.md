---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 NameValueWithParametersHeaderValue 类的实例。
type: docs
weight: 79
url: /zh/system.net.http.headers/namevaluewithparametersheadervalue/tryparse/
---
## NameValueWithParametersHeaderValue::TryParse(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) method

尝试将传入的字符串转换为 [NameValueWithParametersHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::NameValueWithParametersHeaderValue::TryParse(String input, System::SharedPtr<NameValueWithParametersHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../)\>\& | 将分配已解析对象的实例。 |

### 返回值

如果解析成功则为 true，否则为 false。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [NameValueWithParametersHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)