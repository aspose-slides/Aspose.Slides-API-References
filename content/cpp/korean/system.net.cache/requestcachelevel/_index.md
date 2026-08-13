---
title: RequestCacheLevel
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 열거형은 모든 WebRequest에 적용되는 캐시 설정을 설명합니다.
type: docs
weight: 27
url: /ko/system.net.cache/requestcachelevel/
---
## RequestCacheLevel 열거형

이 열거형은 모든 [WebRequest](../../system.net/webrequest/)에 적용되는 캐시 설정을 설명합니다.

```cpp
enum class RequestCacheLevel
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | 0 | 리소스에 대한 요청을 만족시키는 방법은 리소스의 캐시된 복사본을 사용하거나 서버에 요청을 보내는 것입니다. |
| BypassCache | 1 | 서버를 사용하여 요청을 만족시킵니다. 캐시에서 항목을 가져오지 않습니다. |
| CacheOnly | 2 | 리소스에 대한 요청을 캐시에서만 만족시킵니다. 클라이언트 캐시에 리소스가 없을 경우 WebException이 발생합니다. |
| CacheIfAvailable | 3 | 리소스가 사용 가능한 경우 캐시에서 리소스에 대한 요청을 만족시키고, 그렇지 않으면 서버에 요청을 보냅니다. |
| Revalidate | 4 | 클라이언트 타임스탬프가 서버의 리소스 타임스탬프와 동일하면 리소스의 로컬 복사본을 사용합니다. 그렇지 않으면 서버에서 리소스를 다운로드합니다. |
| Reload | 5 | 리소스는 항상 서버에서 다운로드됩니다. |
| NoCacheNoStore | 6 | 캐시의 리소스를 사용하여 요청을 전혀 만족시키지 않으며, 리소스를 캐시하지도 않습니다. |

## 참고

* 네임스페이스 [System::Net::Cache](../)
* 라이브러리 [Aspose.Slides](../../)