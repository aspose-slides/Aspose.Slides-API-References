---
title: GetProductInfoLength()
second_title: Aspose.Slides for C++ API 参考
description: 将传入的字符串从指定索引转换为 ProductInfoHeaderValue 类的实例。
type: docs
weight: 105
url: /zh/system.net.http.headers/productinfoheadervalue/getproductinfolength/
---
## ProductInfoHeaderValue::GetProductInfoLength(String, int32_t, System::SharedPtr\<ProductInfoHeaderValue\>\&) 方法

将传入的字符串从指定索引转换为 [ProductInfoHeaderValue](../) 类的实例。

```cpp
static int32_t System::Net::Http::Headers::ProductInfoHeaderValue::GetProductInfoLength(String input, int32_t startIndex, System::SharedPtr<ProductInfoHeaderValue> &parsedValue)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 要解析的字符串。 |
| startIndex | **int32_t** | 解析的起始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ProductInfoHeaderValue](../)\>\& | 用于接收解析对象的实例。 |

### 返回值

返回已解析子字符串的长度，若未解析则返回 0。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ProductInfoHeaderValue](../)
* 命名空间 [System::Net::Http::Headers](../../)
* 库 [Aspose.Slides](../../../)