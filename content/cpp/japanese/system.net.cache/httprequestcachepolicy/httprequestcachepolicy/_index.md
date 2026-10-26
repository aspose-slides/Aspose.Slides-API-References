---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいインスタンスを作成します。
type: docs
weight: 79
url: /ja/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | リソースのキャッシュ動作。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | リソースのキャッシュ動作を制御します。 |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | 時間の量。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | リソースのキャッシュ動作を制御します。 |
| maxAge | [TimeSpan](../../../system/timespan/) | リソースに許可される最大期限。 |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 時間の量。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | キャッシュに保存されたリソースが再検証される必要がある時間。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) コンストラクタ

新しいインスタンスを作成します。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | リソースのキャッシュ動作を制御します。 |
| maxAge | [TimeSpan](../../../system/timespan/) | リソースに許可される最大期限。 |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 時間の量。 |
| cacheSyncDate | [DateTime](../../../system/datetime/) | キャッシュに保存されたリソースが再検証される必要がある時間。 |

## 参照

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)