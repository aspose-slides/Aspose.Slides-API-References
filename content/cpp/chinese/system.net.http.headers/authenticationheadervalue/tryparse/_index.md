---
title: TryParse()
second_title: Aspose.Slides C++ API 参考
description: 尝试将传入的字符串转换为 AuthenticationHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/authenticationheadervalue/tryparse/
---
## AuthenticationHeaderValue::TryParse(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [AuthenticationHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::AuthenticationHeaderValue::TryParse(String input, System::SharedPtr<AuthenticationHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[AuthenticationHeaderValue](../)\>\& | 将分配已解析对象的实例。 |

### 返回值

解析成功时返回 true，否则返回 false。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [AuthenticationHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)