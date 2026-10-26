---
title: HttpCacheAgeControl
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: CacheAgeControl ใช้เพื่อระบุการตั้งค่าที่เกี่ยวกับอายุและความสดของรายการที่อยู่ในแคช.
type: docs
weight: 53
url: /th/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl is used to specify preferences with respect of cached item age and freshness.

```cpp
enum class HttpCacheAgeControl
```

### ค่า

| ชื่อ | ค่า | คำอธิบาย |
| --- | --- | --- |
| None | 0 | ใช้สำหรับภายในเท่านั้น. |
| MinFresh | 1 | สามารถดึงเนื้อหาจากแคชได้หากเวลาที่เหลือก่อนหมดอายุมากกว่าหรือเท่ากับค่าที่กำหนดไว้ด้วยค่านี้. |
| MaxAge | 2 | สามารถดึงเนื้อหาจากแคชได้จนกว่าจะเก่ากว่าค่าที่กำหนดด้วยค่านี้. |
| MaxStale | 4 | สามารถดึงเนื้อหาจากแคชได้หลังจากที่หมดอายุจนกว่าจะถึงเวลาที่กำหนดด้วยค่านี้. |
| MaxAgeAndMinFresh | 3 | MaxAge และ MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge และ MaxStale. |

## ดูเพิ่มเติม

* Namespace [System::Net::Cache](../)
* Library [Aspose.Slides](../../)