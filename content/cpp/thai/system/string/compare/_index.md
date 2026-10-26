---
title: Compare()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เปรียบเทียบสองส่วนย่อยโดยใช้การน้อย-เท่า-มาก.
type: docs
weight: 820
url: /th/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) method

เปรียบเทียบสองส่วนย่อยโดยใช้การน้อย-เท่า-มาก

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องการเปรียบเทียบ |
| indexA | int | จุดเริ่มต้นของส่วนย่อยสตริงแรก |
| strB | const [String](../)\& | สตริงที่สองที่ต้องการเปรียบเทียบ |
| indexB | int | จุดเริ่มต้นของส่วนย่อยสตริงที่สอง |
| length | int | จำนวนอักขระที่ต้องการเปรียบเทียบ |
| ignoreCase | **bool** | ระบุว่าการเปรียบเทียบควรไม่สนใจตัวพิมพ์ใหญ่-เล็ก |

### ค่าที่คืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method

เปรียบเทียบสองส่วนย่อยโดยใช้การน้อย-เท่า-มาก

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องการเปรียบเทียบ |
| indexA | int | จุดเริ่มต้นของส่วนย่อยสตริงแรก |
| strB | const [String](../)\& | สตริงที่สองที่ต้องการเปรียบเทียบ |
| indexB | int | จุดเริ่มต้นของส่วนย่อยสตริงที่สอง |
| length | int | จำนวนอักขระที่ต้องการเปรียบเทียบ |
| ignoreCase | **bool** | ระบุว่าการเปรียบเทียบควรไม่สนใจตัวพิมพ์ใหญ่-เล็ก |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่จะใช้ในการเปรียบเทียบ |

### ค่าที่คืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าสส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## String::Compare(const String\&, const String\&, System::StringComparison) method

เปรียบเทียบสองสตริงโดยใช้การน้อย-เท่า-มาก

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องการเปรียบเทียบ |
| strB | const [String](../)\& | สตริงที่สองที่ต้องการเปรียบเทียบ |
| comparison_type | [System::StringComparison](../../stringcomparison/) | โหมด [Comparison](../../comparison/) |

### ค่าที่คืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าสส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) method

เปรียบเทียบสองสตริงโดยใช้การน้อย-เท่า-มาก

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องการเปรียบเทียบ |
| indexA | int | จุดเริ่มต้นของส่วนย่อยสตริงแรก |
| strB | const [String](../)\& | สตริงที่สองที่ต้องการเปรียบเทียบ |
| indexB | int | จุดเริ่มต้นของส่วนย่อยสตริงที่สอง |
| length | int | จำนวนอักขระที่ต้องการเปรียบเทียบ |
| comparison_type | [System::StringComparison](../../stringcomparison/) | โหมด [Comparison](../../comparison/) |

### ค่าที่คืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าสส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## String::Compare(const String\&, const String\&, bool) method

เปรียบเทียบสองสตริงโดยใช้การน้อย-เท่า-มาก

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องการเปรียบเทียบ |
| strB | const [String](../)\& | สตริงที่สองที่ต้องการเปรียบเทียบ |
| ignoreCase | **bool** | ระบุว่าการเปรียบเทียบควรไม่สนใจตัวพิมพ์ใหญ่-เล็ก |

### ค่าที่คืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าสส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) method

เปรียบเทียบสองสตริงโดยใช้การน้อย-เท่า-มาก

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| strA | const [String](../)\& | สตริงแรกที่ต้องการเปรียบเทียบ |
| strB | const [String](../)\& | สตริงที่สองที่ต้องการเปรียบเทียบ |
| ignoreCase | **bool** | ระบุว่าการเปรียบเทียบควรไม่สนใจตัวพิมพ์ใหญ่-เล็ก |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | วัฒนธรรมที่จะใช้ในการเปรียบเทียบ |

### ค่าที่คืน

ค่าติดลบหากส่วนย่อยแรกน้อยกว่าสส่วนย่อยที่สอง, ศูนย์หากเท่ากัน, ค่าบวกในกรณีอื่น

## See Also

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)