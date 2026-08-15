---
title: UriComponents
second_title: Aspose.Slides for C++ API 參考文件
description: 表示 URI 元件。
type: docs
weight: 3251
url: /zh-hant/system/uricomponents/
---
## UriComponents 列舉

表示 URI 元件。

```cpp
enum class UriComponents
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Scheme | 1 | Scheme 資料。 |
| UserInfo | 2 | UserInfo 資料。 |
| Host | 4 | Host 資料。 |
| Port | 8 | Port 資料。 |
| SchemeAndServer | n/a | Scheme、Host 和 Port 資料。 |
| Path | 16 | LocalPath 資料。 |
| Query | 32 | Query 資料。 |
| PathAndQuery | n/a | LocalPath 和 Query 資料。 |
| HttpRequestUrl | n/a | Scheme、Host、Port、Query 和 LocalPath 資料。 |
| Fragment | 64 | Fragment 資料。 |
| AbsoluteUri | n/a | Scheme、Host、Port、Quer、LocalPath 和 Fragment 資料。 |
| StrongPort | 128 | Port 資料；如果在 [Uri](../uri/) 中未出現 Port 資料且已為 Scheme 指派預設埠，則回傳預設埠；如果沒有預設埠，則回傳 -1。 |
| HostAndPort | n/a | Host 和 Port 資料；如果在 [Uri](../uri/) 中未出現 Port 資料且已為 Scheme 指派預設埠，則回傳預設埠。如果沒有預設埠，則回傳 -1。 |
| StrongAuthority | n/a | UserInfo、Host 和 Port 資料。如果在 [Uri](../uri/) 中沒有 Port 資料且已為 Scheme 指派預設埠，則回傳預設埠。如果沒有預設埠，則回傳 -1。 |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | 指定應該包含分隔符。 |
| SerializationInfoString | n/a | 完整的 [Uri](../uri/) 上下文，為 [Uri](../uri/) 序列化器所需。上下文包含 IPv6 範圍。 |

## 另請參閱

* Namespace [System](../)
* Library [Aspose.Slides](../../)