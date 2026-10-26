---
title: MakeRelativeUri()
second_title: Aspose.Slides C++ API 参考
description: 确定当前对象和指定的 Uri 对象所表示的 URI 之间的差异。
type: docs
weight: 352
url: /zh/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) method

确定当前对象和指定的 [Uri](../) 对象所表示的 URI 之间的差异。

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | 比较对象 |

### 返回值

如果当前对象和 **toUri** 所表示的 URI 的主机名和方案相同，则此方法返回一个相对 [Uri](../)，当将其附加到当前 URI 实例时，会得到 **toUri**。如果主机名或方案不同，则此方法返回一个表示 **uri** 参数的 [Uri](../) 对象。

## 另请参阅

* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [Uri](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)