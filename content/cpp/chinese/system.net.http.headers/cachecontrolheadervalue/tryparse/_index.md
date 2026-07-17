---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 CacheControlHeaderValue 类的实例。
type: docs
weight: 443
url: /zh/system.net.http.headers/cachecontrolheadervalue/tryparse/
---
## CacheControlHeaderValue::TryParse(String, System::SharedPtr\<CacheControlHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [CacheControlHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::CacheControlHeaderValue::TryParse(String input, System::SharedPtr<CacheControlHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[CacheControlHeaderValue](../)\>\& | 解析后对象将被赋值的实例。 |

### 返回值

如果解析成功则返回 true，否则返回 false。

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [CacheControlHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)