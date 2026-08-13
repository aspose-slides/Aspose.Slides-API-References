---
title: HttpCacheAgeControl
second_title: Aspose.Slides for C++ API 레퍼런스
description: CacheAgeControl은 캐시된 항목의 연령 및 신선도와 관련된 기본 설정을 지정하는 데 사용됩니다.
type: docs
weight: 53
url: /ko/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl 열거형

CacheAgeControl은 캐시된 항목의 연령 및 신선도와 관련된 기본 설정을 지정하는 데 사용됩니다.

```cpp
enum class HttpCacheAgeControl
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 내부 전용입니다. |
| MinFresh | 1 | 만료까지 남은 시간이 이 값에 지정된 시간보다 크거나 같으면 캐시에서 콘텐츠를 가져올 수 있습니다. |
| MaxAge | 2 | 이 값에 지정된 연령보다 오래될 때까지 캐시에서 콘텐츠를 가져올 수 있습니다. |
| MaxStale | 4 | 만료된 후에도 이 값에 지정된 시간이 경과할 때까지 캐시에서 콘텐츠를 가져올 수 있습니다. |
| MaxAgeAndMinFresh | 3 | MaxAge와 MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge와 MaxStale. |

## 참고

* 네임스페이스 [System::Net::Cache](../)
* 라이브러리 [Aspose.Slides](../../)