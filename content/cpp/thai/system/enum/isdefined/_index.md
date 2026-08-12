---
title: IsDefined()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดว่าค่าที่ระบุเป็นสมาชิกของประเภท enumeration E หรือไม่
type: docs
weight: 27
url: /th/system/enum/isdefined/
---
## Enum::IsDefined(E) เมธอด

กำหนดว่าค่าที่ระบุเป็นสมาชิกของประเภท enumeration **E** หรือไม่

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | E | ค่าที่ต้องการตรวจสอบ |

### Return Value

True หาก **value** เป็นสมาชิกของ enumeration **E**, มิฉะนั้น - false

## Enum::IsDefined(T) เมธอด

กำหนดว่าค่าที่ระบุเป็นสมาชิกของประเภท enumeration **T** หรือไม่

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | ค่าที่ต้องการตรวจสอบ |

### Return Value

True หาก **value** เป็นสมาชิกของ enumeration **T**, มิฉะนั้น - false

## Enum::IsDefined(const String\&) เมธอด

กำหนดว่าค่าที่มีชื่อที่ระบุอยู่ในสมาชิกของ enum **E** หรือไม่

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| name | const [String](../../string/)\& | ชื่อที่ต้องการตรวจสอบ |

### Return Value

True หากมีสมาชิกของ enum **E** ที่มีชื่อที่ระบุ

## ดูเพิ่มเติม

* Typedef [UnderlyingType](../underlyingtype/)
* คลาส [String](../../string/)
* Struct [Enum](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)