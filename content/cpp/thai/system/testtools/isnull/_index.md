---
title: IsNull()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าค่าที่ระบุเป็น null หรือไม่ รุ่นสำหรับประเภทเชิงคณิตศาสตร์และ enum
type: docs
weight: 1
url: /th/system/testtools/isnull/
---
## TestTools::IsNull(T) เมธอด

ตรวจสอบว่าค่าที่ระบุเป็น null หรือไม่ [Version](../../version/) สำหรับประเภทเชิงคณิตศาสตร์และ enum

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของค่าที่กำลังตรวจสอบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | T | ค่าที่จะตรวจสอบว่าเป็น null |

### ค่าที่คืน

จะคืนค่า false เสมอ

## TestTools::IsNull(const T\&) เมธอด

ตรวจสอบว่าค่าที่ระบุเป็น null หรือไม่ [Version](../../version/) สำหรับประเภทค่าไม่ใช่เชิงคณิตศาสตร์และไม่ใช่ enum

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของค่าที่กำลังตรวจสอบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const T\& | ค่าที่จะตรวจสอบว่าเป็น null |

### ค่าที่คืน

คืนค่า true หากอ็อบเจกต์ถูกเปรียบเทียบกับ nullptr เป็น true, มิฉะนั้นคืนค่า false

## TestTools::IsNull(const SharedPtr\<T\>\&) เมธอด

ตรวจสอบว่าค่าที่ระบุเป็น null หรือไม่ [Version](../../version/) สำหรับประเภทค่าที่ไม่ใช่เชิงคณิตศาสตร์

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของค่าที่กำลังตรวจสอบ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | ค่าที่จะตรวจสอบว่าเป็น null |

### ค่าที่คืน

คืนค่า true หากอ็อบเจกต์ถูกเปรียบเทียบกับ nullptr เป็น true, มิฉะนั้นคืนค่า false

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) เมธอด

ตรวจสอบว่าค่าที่ระบุเป็น null หรือไม่ [Version](../../version/) สำหรับคู่คีย์ค่า

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ประเภทคีย์ |
| V | ประเภทค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | วัตถุคู่ |

### ค่าที่คืน

คืนค่า true หากคู่ถือเป็น null, มิฉะนั้นคืนค่า false

## TestTools::IsNull(const System::String\&) เมธอด

ตรวจสอบว่า string เป็น null หรือไม่

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) to check |

### ค่าที่คืน

คืนค่า true หากสตริงถือเป็น null, มิฉะนั้นคืนค่า false

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* คลาส [String](../../string/)
* โครงสร้าง [TestTools](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)