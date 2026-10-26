---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ API 참조
description: 새 인스턴스를 생성합니다.
type: docs
weight: 79
url: /ko/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | 리소스에 대한 캐싱 동작입니다. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 리소스에 대한 캐싱 동작을 제어합니다. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | 시간량입니다. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 리소스에 대한 캐싱 동작을 제어합니다. |
| maxAge | [TimeSpan](../../../system/timespan/) | 리소스에 허용되는 최대 수명입니다. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 시간량입니다. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | 캐시된 리소스를 재검증해야 하는 시점입니다. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 리소스에 대한 캐싱 동작을 제어합니다. |
| maxAge | [TimeSpan](../../../system/timespan/) | 리소스에 허용되는 최대 수명입니다. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 시간량입니다. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | 캐시된 리소스를 재검증해야 하는 시점입니다. |

## 참고

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)