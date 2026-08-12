---
title: HttpRequestCachePolicy()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: สร้างอินสแตนซ์ใหม่.
type: docs
weight: 79
url: /th/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | พฤติกรรมการแคชสำหรับทรัพยากร |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | ควบคุมพฤติกรรมการแคชสำหรับทรัพยากร |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | ช่วงเวลา |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | ควบคุมพฤติกรรมการแคชสำหรับทรัพยากร |
| maxAge | [TimeSpan](../../../system/timespan/) | อายุสูงสุดที่อนุญาตสำหรับทรัพยากร |
| freshOrStale | [TimeSpan](../../../system/timespan/) | ช่วงเวลา |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | เวลาที่ต้องทำการตรวจสอบความถูกต้องของทรัพยากรที่จัดเก็บในแคช |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) คอนสตรักเตอร์

สร้างอินสแตนซ์ใหม่

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | ควบคุมพฤติกรรมการแคชสำหรับทรัพยากร |
| maxAge | [TimeSpan](../../../system/timespan/) | อายุสูงสุดที่อนุญาตสำหรับทรัพยากร |
| freshOrStale | [TimeSpan](../../../system/timespan/) | ช่วงเวลา |
| cacheSyncDate | [DateTime](../../../system/datetime/) | เวลาที่ต้องทำการตรวจสอบความถูกต้องของทรัพยากรที่จัดเก็บในแคช |

## ดูเพิ่มเติม

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)