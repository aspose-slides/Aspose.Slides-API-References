---
title: HttpRequestCacheLevel
second_title: Aspose.Slides for C++ API 참조
description: 이 열거형은 HTTP에 대한 캐시 설정을 설명합니다.
type: docs
weight: 40
url: /ko/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel 열거형

이 열거형은 HTTP에 대한 캐시 설정을 설명합니다.

```cpp
enum class HttpRequestCacheLevel
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | 0 | 리소스에 대한 요청을 캐시된 복사본을 사용하거나 리소스를 서버에 요청함으로써 만족시킵니다. |
| BypassCache | 1 | 서버를 사용하여 요청을 만족시킵니다. |
| CacheOnly | 2 | 항상 클라이언트 캐시를 사용하여 리소스를 가져옵니다. |
| CacheIfAvailable | 3 | 리소스가 캐시에서 사용 가능하면 캐시에서 요청을 만족시키고, 그렇지 않으면 서버에 요청을 보냅니다. |
| Revalidate | 4 | 클라이언트 타임스탬프가 서버에 있는 리소스의 타임스탬프와 동일한 경우 리소스의 로컬 복사본을 사용합니다. 그렇지 않으면 서버에서 리소스를 다운로드합니다. |
| Reload | 5 | 리소스는 항상 서버에서 다운로드됩니다. |
| NoCacheNoStore | 6 | 캐시에서 리소스를 사용하여 요청을 만족시키지 않으며, 리소스를 캐시하지도 않습니다. |
| CacheOrNextCacheOnly | 7 | 리소스에 대한 요청을 로컬 컴퓨터의 캐시 또는 LAN상의 원격 캐시 중 하나에서 만족시킵니다. |
| Refresh | 8 | 서버 또는 로컬 캐시 이외의 캐시를 사용하여 요청을 만족시킵니다. |

## 참고

* 네임스페이스 [System::Net::Cache](../)
* 라이브러리 [Aspose.Slides](../../)