---
title: Compare()
second_title: Aspose.Slides for C++ API 参考
description: 使用指定的比较规则比较指定的 Uri 对象。
type: docs
weight: 521
url: /zh/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) 方法

使用指定的比较规则比较指定的 [Uri](../) 对象。

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 第一个比较对象 |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 第二个比较对象 |
| partsToCompare | [UriComponents](../../uricomponents/) | 指定要比较的 **uri1** 和 **uri2** 的部分 |
| compareFormat | [UriFormat](../../uriformat/) | 指定在比较 URI 组件时使用的字符转义方式 |
| comparisonType | [StringComparison](../../stringcomparison/) | StringComparison 的一个取值 |

### 返回值

如果 **uri1** 小于 **uri2** 则返回负值；如果 uri1 和 uri2 相等则返回 0；如果 **uri1** 大于 **uri2** 则返回正值

## 另请参见

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* 类 [Uri](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)