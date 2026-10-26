---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: एक नया इंस्टेंस बनाता है।
type: docs
weight: 79
url: /hi/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() कंस्ट्रक्टर


एक नया इंस्टेंस बनाता है।

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) कंस्ट्रक्टर


एक नया इंस्टेंस बनाता है।

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | संसाधनों के लिए कैशिंग व्यवहार। |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) कंस्ट्रक्टर


एक नया इंस्टेंस बनाता है।

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | संसाधनों के लिए कैशिंग व्यवहार को नियंत्रित करता है। |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | समय की मात्रा। |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) कंस्ट्रक्टर


एक नया इंस्टेंस बनाता है।

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | संसाधनों के लिए कैशिंग व्यवहार को नियंत्रित करता है। |
| maxAge | [TimeSpan](../../../system/timespan/) | संसाधनों के लिए निर्धारित अधिकतम आयु। |
| freshOrStale | [TimeSpan](../../../system/timespan/) | समय की मात्रा। |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) कंस्ट्रक्टर


एक नया इंस्टेंस बनाता है।

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | कैश में संग्रहीत संसाधनों को पुनः सत्यापित करने का समय। |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) कंस्ट्रक्टर


एक नया इंस्टेंस बनाता है।

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | संसाधनों के लिए कैशिंग व्यवहार को नियंत्रित करता है। |
| maxAge | [TimeSpan](../../../system/timespan/) | संसाधनों के लिए निर्धारित अधिकतम आयु। |
| freshOrStale | [TimeSpan](../../../system/timespan/) | समय की मात्रा। |
| cacheSyncDate | [DateTime](../../../system/datetime/) | कैश में संग्रहीत संसाधनों को पुनः सत्यापित करने का समय। |

## संबंधित देखें

* एनम [HttpRequestCacheLevel](../../httprequestcachelevel/)
* एनम [HttpCacheAgeControl](../../httpcacheagecontrol/)
* क्लास [HttpRequestCachePolicy](../)
* क्लास [TimeSpan](../../../system/timespan/)
* क्लास [DateTime](../../../system/datetime/)
* नेमस्पेस [System::Net::Cache](../../)
* लाइब्रेरी [Aspose.Slides](../../../)