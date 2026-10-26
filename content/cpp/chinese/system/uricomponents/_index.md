---
title: UriComponents
second_title: Aspose.Slides C++ API 参考
description: 表示 URI 组件。
type: docs
weight: 3212
url: /zh/system/uricomponents/
---
## UriComponents 枚举

表示 URI 组件。

```cpp
enum class UriComponents
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Scheme | 1 | Scheme 数据。 |
| UserInfo | 2 | UserInfo 数据。 |
| Host | 4 | Host 数据。 |
| Port | 8 | Port 数据。 |
| SchemeAndServer | n/a | Scheme、Host 和 Port 数据。 |
| Path | 16 | LocalPath 数据。 |
| Query | 32 | Query 数据。 |
| PathAndQuery | n/a | LocalPath 和 Query 数据。 |
| HttpRequestUrl | n/a | Scheme、Host、Port、Query 和 LocalPath 数据。 |
| Fragment | 64 | Fragment 数据。 |
| AbsoluteUri | n/a | Scheme、Host、Port、Quer、LocalPath 和 Fragment 数据。 |
| StrongPort | 128 | Port 数据；如果在 [Uri](../uri/) 中不存在 port 数据且已为 Scheme 分配了默认端口，则返回默认端口；如果没有默认端口，则返回 -1。 |
| HostAndPort | n/a | Host 和 Port 数据；如果在 [Uri](../uri/) 中不存在 port 数据且已为 Scheme 分配了默认端口，则返回默认端口。如果没有默认端口，则返回 -1。 |
| StrongAuthority | n/a | UserInfo、Host 和 Port 数据。如果在 [Uri](../uri/) 中不存在 port 数据且已为 Scheme 分配了默认端口，则返回默认端口。如果没有默认端口，则返回 -1。 |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | 指定应包括分隔符。 |
| SerializationInfoString | n/a | 完整的 [Uri](../uri/) 上下文，供 [Uri](../uri/) 序列化器使用。上下文包括 IPv6 作用域。 |

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)