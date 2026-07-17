---
title: MakeRelative()
second_title: Aspose.Slides for C++ API 参考
description: 确定两个 Uri 实例之间的差异。
type: docs
weight: 365
url: /zh/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) 方法

确定两个[Uri](../)实例之间的差异。

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 用于与当前 URI 比较的 URI |

### 返回值

如果当前对象和 **toUri** 所表示的 URI 的主机名和方案相同，则此方法返回一个 [String](../../string/)，该对象表示一个相对的 [Uri](../)，当将其附加到当前 URI 实例时，会得到 **toUri**。如果主机名或方案不同，则此方法返回一个 [String](../../string/)，该对象表示 **uri** 参数。

## 另请参见

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../../string/)
* 类 [Uri](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)