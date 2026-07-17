---
title: GetNameValueListLength()
second_title: Aspose.Slides C++ API 参考
description: 将传入的字符串从指定索引转换为 NameValueHeaderValue 类实例的集合，并返回已解析子字符串的长度。
type: docs
weight: 131
url: /zh/system.net.http.headers/namevalueheadervalue/getnamevaluelistlength/
---
## NameValueHeaderValue::GetNameValueListLength(String, int32_t, char16_t, System::SharedPtr\<ObjectCollection\<System::SharedPtr\<NameValueHeaderValue\>\>\>) 方法


将传入的字符串从指定索引转换为 NameValueHeaderValue 类实例的集合，并返回已解析子字符串的长度。

```cpp
static int32_t System::Net::Http::Headers::NameValueHeaderValue::GetNameValueListLength(String input, int32_t startIndex, char16_t delimiter, System::SharedPtr<ObjectCollection<System::SharedPtr<NameValueHeaderValue>>> nameValueCollection)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要分析的字符串。 |
| startIndex | **int32_t** | 用于分析的起始位置。 |
| delimiter | char16_t | 用于分隔指定字符串中项目的字符串。 |
| nameValueCollection | [System::SharedPtr](../../../system/sharedptr/)\<[ObjectCollection](../../objectcollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\>\> | 解析后集合将被分配的输出参数。 |

### 返回值

已解析子字符串的长度。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ObjectCollection](../../objectcollection/)
* 类 [NameValueHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)