---
title: Storage
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นการจัดเก็บข้อมูลชั่วคราวสำหรับ .
type: docs
url: /th/com.aspose.slides/storage/
---
**Inheritance:**
java.lang.Object
```
public final class Storage
```

เป็นการจัดเก็บข้อมูลชั่วคราวสำหรับ [WebDocument](../../com.aspose.slides/webdocument).
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [Storage()](#Storage--) |  |
## เมธอด

| Method | Description |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Puts the value into the storage. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Gets the data from the storage. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Determines whether the storage contains an element with the specified key. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


ใส่ค่าลงในที่จัดเก็บ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key for the value. |
| value | TValue | Value. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


ดึงข้อมูลจากที่จัดเก็บ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key of the value. |

**Returns:**
TValue - Data value if it is presented in the data collection, null otherwise.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


ตรวจสอบว่าที่จัดเก็บมีองค์ประกอบที่มีคีย์ที่ระบุหรือไม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | Key of the value. |

**Returns:**
boolean - True if the storage contains an element with the specified key, false otherwise.