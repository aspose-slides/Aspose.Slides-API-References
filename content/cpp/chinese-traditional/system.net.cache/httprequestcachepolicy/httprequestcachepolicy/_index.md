---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ API 參考
description: 建立新實例。
type: docs
weight: 79
url: /zh-hant/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() 建構函式

建立新實例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) 建構函式

建立新實例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | 資源的快取行為。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) 建構函式

建立新實例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 控制資源的快取行為。 |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | 時間量。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) 建構函式

建立新實例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 控制資源的快取行為。 |
| maxAge | [TimeSpan](../../../system/timespan/) | 資源允許的最大年齡。 |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 時間量。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) 建構函式

建立新實例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | 快取中存儲的資源必須重新驗證的時間。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) 建構函式

建立新實例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 控制資源的快取行為。 |
| maxAge | [TimeSpan](../../../system/timespan/) | 資源允許的最大年齡。 |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 時間量。 |
| cacheSyncDate | [DateTime](../../../system/datetime/) | 快取中存儲的資源必須重新驗證的時間。 |

## 另請參閱

* 列舉 [HttpRequestCacheLevel](../../httprequestcachelevel/)
* 列舉 [HttpCacheAgeControl](../../httpcacheagecontrol/)
* 類別 [HttpRequestCachePolicy](../)
* 類別 [TimeSpan](../../../system/timespan/)
* 類別 [DateTime](../../../system/datetime/)
* 命名空間 [System::Net::Cache](../../)
* 函式庫 [Aspose.Slides](../../../)