---
title: Equals()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: การเปรียบเทียบความเท่าเทียมของสตริง. รองรับหลายโหมดที่จัดให้โดยการอธิบาย StringComparison
type: docs
weight: 391
url: /th/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const เมธอด


[String](../) การเปรียบเทียบความเท่าเทียม. รองรับหลายโหมดที่จัดเตรียมโดยการอธิบาย StringComparison

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) เพื่อเปรียบเทียบกับอันที่กำลังใช้อยู่. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด (ดู [System::StringComparison](../../stringcomparison/) สำหรับรายละเอียด). |

### ค่าที่คืน

true หากสตริงตรงกันโดยใช้ประเภทการเปรียบเทียบที่เลือก, false หากไม่ตรงกัน.

## String::Equals(const String\&) const เมธอด


[String](../) การเปรียบเทียบความเท่าเทียม. ใช้โหมดการเปรียบเทียบ [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) เพื่อเปรียบเทียบกับอันที่กำลังใช้อยู่. |

### ค่าที่คืน

true หากสตริงตรงกัน, false หากไม่ตรงกัน.

## String::Equals(const String\&, const String\&) เมธอด


Equal-compares two strings using Ordial comparison mode.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกเพื่อเปรียบเทียบ. |
| strB | const [String](../)\& | สตริงที่สองเพื่อเปรียบเทียบ. |

### ค่าที่คืน

true หากสตริงตรงกัน, false หากไม่ตรงกัน.

## String::Equals(const String\&, const String\&, System::StringComparison) เมธอด


```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกเพื่อเปรียบเทียบ. |
| strB | const [String](../)\& | สตริงที่สองเพื่อเปรียบเทียบ. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) โหมด. |

### ค่าที่คืน

true หากสตริงตรงกัน, false หากไม่ตรงกัน.

## ดูเพิ่มเติม

* Enum [StringComparison](../../stringcomparison/)
* คลาส [String](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)