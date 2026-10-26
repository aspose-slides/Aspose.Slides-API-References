---
title: Guid()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างอ็อบเจ็กต์ที่เป็นตัวแทนของ GUID ที่ประกอบด้วยศูนย์ทั้งหมด.
type: docs
weight: 1
url: /th/system/guid/guid/
---
## Guid::Guid() คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ที่เป็นตัวแทนของ GUID ที่ประกอบด้วยศูนย์ทั้งหมด.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ที่เป็นตัวแทนของ GUID ที่ระบุเป็นอาร์เรย์ของค่าจำนวนเต็มแบบไม่มีเครื่องหมาย 8 บิต.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่ประกอบด้วยไบต์แยกของ GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ที่เป็นตัวแทนของ GUID ที่ระบุเป็นมุมมองอาร์เรย์ของค่าจำนวนเต็มแบบไม่มีเครื่องหมาย 8 บิต.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่ประกอบด้วยไบต์แยกของ GUID |

## Guid::Guid(const String\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ที่เป็นตัวแทนของ GUID ที่ระบุเป็นสตริง.

```cpp
System::Guid::Guid(const String &g)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| g | const [String](../../string/)\& | การแทนค่าด้วยสตริงของ GUID ที่จะโดยอ็อบเจ็กต์ที่กำลังสร้าง |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของคลาส [Guid](../) จากส่วนประกอบของ GUID ที่ระบุ.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | **int32_t** | บิต 0-31 ของ GUID |
| b | **int16_t** | บิต 32-47 ของ GUID |
| c | **int16_t** | บิต 48-63 ของ GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | อาร์เรย์ของไบต์ที่ประกอบด้วยบิต 64-127 ของ GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของคลาส [Guid](../) จากส่วนประกอบของ GUID ที่ระบุ.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | **int32_t** | บิต 0-31 ของ GUID |
| b | **int16_t** | บิต 32-47 ของ GUID |
| c | **int16_t** | บิต 48-63 ของ GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | มุมมองอาร์เรย์ของไบต์ที่ประกอบด้วยบิต 64-127 ของ GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของคลาส [Guid](../) จากจำนวนเต็มบวกและไบต์ที่ระบุ.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | **int32_t** | บิต 0-31 ของ GUID |
| b | **int16_t** | บิต 32-47 ของ GUID |
| c | **int16_t** | บิต 48-63 ของ GUID |
| d | **uint8_t** | บิต 64-71 ของ GUID |
| e | **uint8_t** | บิต 72-79 ของ GUID |
| f | **uint8_t** | บิต 80-87 ของ GUID |
| g | **uint8_t** | บิต 88-95 ของ GUID |
| h | **uint8_t** | บิต 96-103 ของ GUID |
| i | **uint8_t** | บิต 104-111 ของ GUID |
| j | **uint8_t** | บิต 112-119 ของ GUID |
| k | **uint8_t** | บิต 120-127 ของ GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) คอนสตรัคเตอร์

สร้างอินสแตนซ์ของคลาส [Guid](../) จากจำนวนเต็มบวกและไบต์ที่ระบุ.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| a | **uint32_t** | บิต 0-31 ของ GUID |
| b | **uint16_t** | บิต 32-47 ของ GUID |
| c | **uint16_t** | บิต 48-63 ของ GUID |
| d | **uint8_t** | บิต 64-71 ของ GUID |
| e | **uint8_t** | บิต 72-79 ของ GUID |
| f | **uint8_t** | บิต 80-87 ของ GUID |
| g | **uint8_t** | บิต 88-95 ของ GUID |
| h | **uint8_t** | บิต 96-103 ของ GUID |
| i | **uint8_t** | บิต 104-111 ของ GUID |
| j | **uint8_t** | บิต 112-119 ของ GUID |
| k | **uint8_t** | บิต 120-127 ของ GUID |

## Guid::Guid(const Guid\&) คอนสตรัคเตอร์

สร้างอ็อบเจ็กต์ที่เป็นตัวแทนของ GUID เดียวกันกับอ็อบเจ็กต์ที่ระบุ.

```cpp
System::Guid::Guid(const Guid &guid)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| guid | const [Guid](../)\& | อ็อบเจ็กต์ [Guid](../) ที่จะคัดลอกค่า GUID จาก |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)