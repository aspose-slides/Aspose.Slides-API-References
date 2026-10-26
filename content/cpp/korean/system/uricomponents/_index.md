---
title: UriComponents
second_title: Aspose.Slides for C++ API 참조
description: URI 구성 요소를 나타냅니다.
type: docs
weight: 3251
url: /ko/system/uricomponents/
---
## UriComponents 열거형

URI 구성 요소를 나타냅니다.

```cpp
enum class UriComponents
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Scheme | 1 | Scheme 데이터입니다. |
| UserInfo | 2 | UserInfo 데이터입니다. |
| Host | 4 | Host 데이터입니다. |
| Port | 8 | Port 데이터입니다. |
| SchemeAndServer | n/a | Scheme, Host 및 Port 데이터입니다. |
| Path | 16 | LocalPath 데이터입니다. |
| Query | 32 | Query 데이터입니다. |
| PathAndQuery | n/a | LocalPath 및 Query 데이터입니다. |
| HttpRequestUrl | n/a | Scheme, Host, Port, Query 및 LocalPath 데이터입니다. |
| Fragment | 64 | Fragment 데이터입니다. |
| AbsoluteUri | n/a | Scheme, Host, Port, Quer, LocalPath 및 Fragment 데이터입니다. |
| StrongPort | 128 | Port 데이터; 포트 데이터가 [Uri](../uri/)에 없고 기본 포트가 Scheme에 할당된 경우 기본 포트가 반환됩니다; 기본 포트가 없으면 -1이 반환됩니다. |
| HostAndPort | n/a | Host 및 Port 데이터; 포트 데이터가 [Uri](../uri/)에 없고 기본 포트가 Scheme에 할당된 경우 기본 포트가 반환됩니다. 기본 포트가 없으면 -1이 반환됩니다. |
| StrongAuthority | n/a | UserInfo, Host 및 Port 데이터. 포트 데이터가 [Uri](../uri/)에 없고 기본 포트가 Scheme에 할당된 경우 기본 포트가 반환됩니다. 기본 포트가 없으면 -1이 반환됩니다. |
| NormalizedHost | 256 |  |
| KeepDelimiter | 1073741824 | 구분자를 포함해야 함을 지정합니다. |
| SerializationInfoString | n/a | [Uri](../uri/) 컨텍스트 전체가 [Uri](../uri/) 직렬 변환기에 필요합니다. 컨텍스트에는 IPv6 범위가 포함됩니다. |

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)