---
title: UriComponents
second_title: Aspose.Slides for C++ API Referansı
description: URI bileşenlerini temsil eder.
type: docs
weight: 3251
url: /tr/system/uricomponents/
---
## UriComponents enum

URI bileşenlerini temsil eder.

```cpp
enum class UriComponents
```

### Values

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Scheme | 1 | Scheme verisi. |
| UserInfo | 2 | UserInfo verisi. |
| Host | 4 | Host verisi. |
| Port | 8 | Port verisi. |
| SchemeAndServer | n/a | Scheme, Host ve Port verileri. |
| Path | 16 | LocalPath verisi. |
| Query | 32 | Query verisi. |
| PathAndQuery | n/a | LocalPath ve Query verileri. |
| HttpRequestUrl | n/a | Scheme, Host, Port, Query ve LocalPath verileri. |
| Fragment | 64 | Fragment verisi. |
| AbsoluteUri | n/a | Scheme, Host, Port, Quer, LocalPath ve Fragment verileri. |
| StrongPort | 128 | Port verisi; port verisi [Uri](../uri/) içinde bulunmuyorsa ve Scheme'e bir varsayılan port atanmışsa, varsayılan port döndürülür; varsayılan port yoksa, -1 döndürülür. |
| HostAndPort | n/a | Host ve Port verileri; port verisi [Uri](../uri/) içinde bulunmuyorsa ve Scheme'e bir varsayılan port atanmışsa, varsayılan port döndürülür. Varsayılan port yoksa, -1 döndürülür. |
| StrongAuthority | n/a | UserInfo, Host ve Port verileri. Port verisi [Uri](../uri/) içinde yoksa ve Scheme'e bir varsayılan port atanmışsa, varsayılan port döndürülür. Varsayılan port yoksa, -1 döndürülür. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Ayırıcı dahil edilmelidir. |
| SerializationInfoString | n/a | [Uri](../uri/) bağlamının tam hali, [Uri](../uri/) Serializers için gereklidir. Bağlam IPv6 kapsamını içerir. |

## Diğerlerine Bakın

* İsim Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)