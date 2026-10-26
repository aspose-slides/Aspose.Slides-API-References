---
title: IsNullOrEmpty()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตรวจสอบว่าคอลเลกชันเป็น null หรือว่าง.
type: docs
weight: 27
url: /th/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) เมธอด


ตรวจสอบว่าคอลเลกชันเป็น null หรือว่าง

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ประเภทของคอลเลกชัน. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | คอลเลกชันที่จะตรวจสอบ. |

### ค่าที่ส่งคืน

คืนค่า true หากคอลเลกชันเป็น null หรือมีจำนวนองค์ประกอบเป็นศูนย์, มิฉะนั้นคืนค่า false.

## TestTools::IsNullOrEmpty(const System::String\&) เมธอด


ตรวจสอบว่าสตริงเป็น null หรือว่าง

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) เพื่อทำการตรวจสอบ. |

### ค่าที่ส่งคืน

คืนค่า true หากสตริงเป็น null หรือมีความยาวเป็นศูนย์, มิฉะนั้นคืนค่า false.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)