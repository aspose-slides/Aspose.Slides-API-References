---
title: CanCast()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ตรวจสอบความเป็นไปได้ของการแคสต์.
type: docs
weight: 40
url: /th/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

Always returns true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

Always returns true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

True if the cast operation was successfully done, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) ฟังก์ชัน

ตรวจสอบความเป็นไปได้ของการแคสต์.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### ค่าที่ส่งคืน

Always returns false.

## ดูเพิ่มเติม

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)