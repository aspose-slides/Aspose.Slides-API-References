---
title: GetAuthenticationLength()
second_title: Aspose.Slides for C++ API 参考
description: 解析指定的字符串并返回字符串表示的最后索引。
type: docs
weight: 118
url: /zh/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength(String, int32_t, System::SharedPtr\<Object\>\&) method


解析指定的字符串并返回字符串表示的最后索引。

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 必须解析的字符串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 将分配解析值的输出参数。 |

### 返回值

已解析子字符串的长度，否则为 0。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [Object](../../../system/object/)
* 类 [AuthenticationHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)