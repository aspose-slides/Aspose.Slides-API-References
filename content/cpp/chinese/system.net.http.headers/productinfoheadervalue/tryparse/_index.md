---
title: TryParse()
second_title: Aspose.Slides for C++ API 参考
description: 尝试将传入的字符串转换为 ProductInfoHeaderValue 类的实例。
type: docs
weight: 92
url: /zh/system.net.http.headers/productinfoheadervalue/tryparse/
---
## ProductInfoHeaderValue::TryParse(String, System::SharedPtr\<ProductInfoHeaderValue\>\&) 方法

尝试将传入的字符串转换为 [ProductInfoHeaderValue](../) 类的实例。

```cpp
static bool System::Net::Http::Headers::ProductInfoHeaderValue::TryParse(String input, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 待解析的字符串。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | 解析后对象将被分配的实例。 |

### 返回值

如果解析成功则返回 true，否则返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ProductInfoHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)