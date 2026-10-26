---
title: Storage
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงที่เก็บข้อมูลชั่วคราวสำหรับ .
type: docs
url: /th/com.aspose.slides/storage/
---
**สืบทอด:**
java.lang.Object
```
public final class Storage
```

แสดงถึงที่เก็บข้อมูลชั่วคราวสำหรับ [WebDocument](../../com.aspose.slides/webdocument).
## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [Storage()](#Storage--) |  |
## เมธอด

| Method | Description |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | ใส่ค่าเข้าไปในที่เก็บข้อมูล. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | ดึงข้อมูลจากที่เก็บ. |
| [containsKey(String key)](#containsKey-java.lang.String-) | กำหนดว่าที่เก็บข้อมูลมีองค์ประกอบที่มีคีย์ที่ระบุหรือไม่. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


ใส่ค่าเข้าไปในที่เก็บข้อมูล.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | คีย์สำหรับค่า. |
| value | TValue | ค่า. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


ดึงข้อมูลจากที่เก็บ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | คีย์ของค่า. |

**คืนค่า:**
TValue - ค่าข้อมูลหากมีอยู่ในคอลเลกชันข้อมูล, null หากไม่มี.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


กำหนดว่าที่เก็บข้อมูลมีองค์ประกอบที่มีคีย์ที่ระบุหรือไม่.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | คีย์ของค่า. |

**คืนค่า:**
boolean - True หากที่เก็บข้อมูลมีองค์ประกอบที่มีคีย์ที่ระบุ, false หากไม่มี.