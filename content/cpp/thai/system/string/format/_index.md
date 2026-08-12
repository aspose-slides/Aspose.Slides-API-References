---
title: Format()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: จัดรูปแบบสตริงในสไตล์ C#.
type: docs
weight: 885
url: /th/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) เมธอด

จัดรูปแบบสตริงในสไตล์ C#.

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Args | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ผู้ให้บริการรูปแบบที่ใช้แปลงอาร์กิวเมนต์เป็นสตริง |
| format | const [String](../)\& | สตริงรูปแบบ |
| args | const Args\&... | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

## String::Format(std::nullptr_t, const String\&, const Args\&...) เมธอด

จัดรูปแบบสตริงในสไตล์ C#.

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Args | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| format | std::nullptr_t | สตริงรูปแบบ |
| args | const [String](../)\& | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) เมธอด

จัดรูปแบบสตริงในสไตล์ C#.

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Args | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| format | std::nullptr_t | สตริงรูปแบบ |
| args | const char16_t(&) | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

## String::Format(const String\&, const Args\&...) เมธอด

จัดรูปแบบสตริงในสไตล์ C#.

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Args | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../)\& | สตริงรูปแบบ |
| args | const Args\&... | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) เมธอด

จัดรูปแบบสตริงในสไตล์ C#.

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| format | const [String](../)\& | สตริงรูปแบบ |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | อาร์กิวเมนต์สำหรับจัดรูปแบบสตริง |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [String](../)
* คลาส [IFormatProvider](../../iformatprovider/)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)