---
title: HttpRequestCachePolicy()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί ένα νέο αντικείμενο.
type: docs
weight: 79
url: /el/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Η συμπεριφορά προσωρινής αποθήκευσης για πόρους. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Ελέγχει τη συμπεριφορά προσωρινής αποθήκευσης για πόρους. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Διάρκεια χρόνου. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Ελέγχει τη συμπεριφορά προσωρινής αποθήκευσης για πόρους. |
| maxAge | [TimeSpan](../../../system/timespan/) | Η μέγιστη επιτρεπόμενη ηλικία για τους πόρους. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Διάρκεια χρόνου. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Η χρονική στιγμή κατά την οποία οι πόροι αποθηκευμένοι στην προσωρινή μνήμη πρέπει να επαληθευτούν. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) κατασκευαστής

Δημιουργεί ένα νέο αντικείμενο.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Ελέγχει τη συμπεριφορά προσωρινής αποθήκευσης για πόρους. |
| maxAge | [TimeSpan](../../../system/timespan/) | Η μέγιστη επιτρεπόμενη ηλικία για τους πόρους. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Διάρκεια χρόνου. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Η χρονική στιγμή κατά την οποία οι πόροι αποθηκευμένοι στην προσωρινή μνήμη πρέπει να επαληθευτούν. |

## Δείτε επίσης

* Απαρίθμηση [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Απαρίθμηση [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Κλάση [HttpRequestCachePolicy](../)
* Κλάση [TimeSpan](../../../system/timespan/)
* Κλάση [DateTime](../../../system/datetime/)
* Χώρος ονομάτων [System::Net::Cache](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)