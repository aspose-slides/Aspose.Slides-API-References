---
title: UriComponents
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili komponen URI.
type: docs
weight: 3251
url: /id/system/uricomponents/
---
## UriComponents enum

Mewakili komponen URI.

```cpp
enum class UriComponents
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Scheme | 1 | Data Scheme. |
| UserInfo | 2 | Data UserInfo. |
| Host | 4 | Data Host. |
| Port | 8 | Data Port. |
| SchemeAndServer | n/a | Data Scheme, Host, dan Port. |
| Path | 16 | Data LocalPath. |
| Query | 32 | Data Query. |
| PathAndQuery | n/a | Data LocalPath dan Query. |
| HttpRequestUrl | n/a | Data Scheme, Host, Port, Query, dan LocalPath. |
| Fragment | 64 | Data Fragment. |
| AbsoluteUri | n/a | Data Scheme, Host, Port, Quer, LocalPath, dan Fragment. |
| StrongPort | 128 | Data Port; jika data port tidak ada dalam [Uri](../uri/) dan port default telah ditetapkan ke Scheme, port default dikembalikan; jika tidak ada port default, -1 dikembalikan. |
| HostAndPort | n/a | Data Host dan Port; jika data port tidak ada dalam [Uri](../uri/) dan port default telah ditetapkan ke Scheme, port default dikembalikan. Jika tidak ada port default, -1 dikembalikan. |
| StrongAuthority | n/a | Data UserInfo, Host, dan Port. Jika tidak ada data port dalam [Uri](../uri/) dan port default telah ditetapkan ke Scheme, port default dikembalikan. Jika tidak ada port default, -1 dikembalikan. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | Menentukan bahwa delimiter harus disertakan. |
| SerializationInfoString | n/a | Konteks lengkap [Uri](../uri/) yang diperlukan untuk Serializers [Uri](../uri/). Konteks mencakup ruang lingkup IPv6. |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)