---
title: Compare()
second_title: Aspose.Slides for C++ API 參考
description: 使用指定的比較規則比較指定的 Uri 物件。
type: docs
weight: 521
url: /zh-hant/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) 方法

比較指定的 [Uri](../) 物件，使用指定的比較規則。

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 第一個比較項 |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 第二個比較項 |
| partsToCompare | [UriComponents](../../uricomponents/) | 指定要比較的 **uri1** 和 **uri2** 的部分 |
| compareFormat | [UriFormat](../../uriformat/) | 指定在比較 URI 組件時使用的字元跳脫方式 |
| comparisonType | [StringComparison](../../stringcomparison/) | StringComparison 值之一 |

### 返回值

如果 **uri1** 小於 **uri2**，則回傳負值；如果 uri1 和 uri2 相等，則回傳 0；如果 **uri1** 大於 **uri2**，則回傳正值

## 另請參閱

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Uri](../)
* 命名空間 [System](../../)
* Library [Aspose.Slides](../../../)