---
title: IterateOver()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับ range-based for loop ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายสำหรับ (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2471
url: /th/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายสำหรับ (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมายที่ต้องส่งค่ากลับจากอิเทอเรเตอร์ |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |

## System::IterateOver(System::SmartPtr\<Enumerable\>) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายค่าเริ่มต้นสำหรับ (auto& value : IterateOver(enumerable)) ซึ่งคล้ายกับโค้ด C# ต่อไปนี้ foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |

## System::IterateOver(System::SmartPtr\<Enumerable\>) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายค่าเริ่มต้นสำหรับ (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |

## System::IterateOver(System::SmartPtr\<Enumerable\>) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่มีเมธอด begin(), end() พร้อมประเภทเป้าหมายเดียวกับ value_type ดั้งเดิมของอิเทอเรเตอร์

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |
| T | ประเภทเป้าหมายที่ต้องส่งค่ากลับจากอิเทอเรเตอร์ |

## System::IterateOver(System::SmartPtr\<Enumerable\>) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่มีเมธอด begin(), end() พร้อมประเภทเป้าหมายที่แตกต่างจาก value_type ดั้งเดิมของอิเทอเรเตอร์

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |
| T | ประเภทเป้าหมายที่ต้องส่งค่ากลับจากอิเทอเรเตอร์ |

## System::IterateOver(const Enumerable *) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable นี้พร้อมประเภทเป้าหมายค่าเริ่มต้น

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |

## System::IterateOver(const Enumerable *) ฟังก์ชัน

คุณสมบัติของฟังก์ชันนี้ห่อหุ้มวัตถุ enumerable (หรือ iterable) เพื่อให้สามารถใช้กับลูปแบบ range-based ได้ การโอเวอร์โหลดนี้สำหรับ Enumerable ที่ไม่มีเมธอด begin(), end() พร้อมอาร์กิวเมนต์ประเภทเป้าหมายสำหรับ (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทเป้าหมายที่ต้องส่งค่ากลับจากอิเทอเรเตอร์ |
| Enumerable | ประเภทของวัตถุที่ห่อหุ้ม |

## ดูเพิ่มเติม

* คลาส [SmartPtr](../smartptr/)
* โครงสร้าง [IsSmartPtr](../issmartptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)