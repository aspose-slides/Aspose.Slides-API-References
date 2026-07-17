---
title: GetCacheControlLength()
second_title: Aspose.Slides for C++ API 参考
description: 将从指定索引开始的传入字符串转换为 CacheControlHeaderValue 类的实例。
type: docs
weight: 456
url: /zh/system.net.http.headers/cachecontrolheadervalue/getcachecontrollength/
---
## CacheControlHeaderValue::GetCacheControlLength(String, int32_t, System::SharedPtr\<CacheControlHeaderValue\>, System::SharedPtr\<CacheControlHeaderValue\>\&) 方法

将从指定索引开始的传入字符串转换为 [CacheControlHeaderValue](../) 类的实例。

```cpp
static int32_t System::Net::Http::Headers::CacheControlHeaderValue::GetCacheControlLength(String input, int32_t startIndex, System::SharedPtr<CacheControlHeaderValue> storeValue, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| storeValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\> | 必须添加到已解析对象的值。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 将分配已解析对象的实例。 |

### 返回值

已解析子字符串的长度，否则为 0。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [CacheControlHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)