---
title: IndexOfAny()
second_title: คู่มืออ้างอิง API ของ Aspose.Slides สำหรับ C++
description: การค้นหาตัวอักษรไปข้างหน้า.
type: docs
weight: 638
url: /th/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const method

การค้นหาตัวอักษรไปข้างหน้า.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | ตัวอักษรที่ต้องการค้นหา. |
| startIndex | int | [Index](../../index/) เพื่อเริ่มการค้นหาที่. |

### ค่าที่ส่งคืน

[Index](../../index/) ของตำแหน่งตัวอักษรแรกตั้งแต่ startIndex หรือ -1 หากไม่พบ.

## String::IndexOfAny(const String\&, int) const method

ดังนั้นจึงค้นหาตัวอักษรทั้งหมดของ str ในอ็อบเจกต์นี้ หากพบตัวอักษรตัวแรกจะส่งตำแหน่งของมันกลับมา มิฉะนั้นจะค้นหาตัวที่สองต่อไปเช่นนั้น

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) ของตัวอักษรที่ต้องการค้นหา. ลำดับของตัวอักษรมีความสำคัญ. |
| startIndex | int | ตำแหน่งเพื่อเริ่มการค้นหาจาก. |

### ค่าที่ส่งคืน

[Index](../../index/) ของตัวอักษรที่พบแรกหรือ -1 หากไม่พบ.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const method

ค้นหาตัวอักษรใด ๆ ที่ส่งมาผ่านสตริงทั้งหมด เปรียบเทียบตัวอักษรแรกของสตริงกับตัวอักษรทั้งหมดใน anyOf จากนั้นเปรียบเทียบตัวที่สองต่อไปเช่นนั้น ส่งคืนดัชนีของตัวแรกที่ตรงกับตัวอักษรเป้าหมายใด ๆ

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของตัวอักษรที่ต้องการค้นหา. ลำดับไม่สำคัญ. |

### ค่าที่ส่งคืน

[Index](../../index/) ของตัวอักษรที่ตรงกันแรกหรือ -1 หากไม่พบ.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

ค้นหาตัวอักษรใด ๆ ที่ส่งมาผ่านส่วนย่อยของสตริง เปรียบเทียบตัวอักษรแรกของสตริงกับตัวอักษรทั้งหมดใน anyOf จากนั้นเปรียบเทียบตัวที่สองต่อไปเช่นนั้น ส่งคืนดัชนีของตัวแรกที่ตรงกับตัวอักษรเป้าหมายใด ๆ

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของตัวอักษรที่ต้องการค้นหา. ลำดับไม่สำคัญ. |
| startindex | **int32_t** | [Index](../../index/) เพื่อเริ่มการค้นหาจาก. |

### ค่าที่ส่งคืน

[Index](../../index/) ของตัวอักษรที่ตรงกันแรกหรือ -1 หากไม่พบ.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

ค้นหาตัวอักษรใด ๆ ที่ส่งมาผ่านส่วนย่อยของสตริง เปรียบเทียบตัวอักษรแรกของสตริงกับตัวอักษรทั้งหมดใน anyOf จากนั้นเปรียบเทียบตัวที่สองต่อไปเช่นนั้น ส่งคืนดัชนีของตัวแรกที่ตรงกับตัวอักษรเป้าหมายใด ๆ

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) ของตัวอักษรที่ต้องการค้นหา. ลำดับไม่สำคัญ. |
| startindex | **int32_t** | [Index](../../index/) เพื่อเริ่มการค้นหาจาก. |
| count | **int32_t** | จำนวนตัวอักษรที่ต้องการค้นหาผ่าน. |

### ค่าที่ส่งคืน

[Index](../../index/) ของตัวอักษรที่ตรงกันแรกหรือ -1 หากไม่พบ.

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)