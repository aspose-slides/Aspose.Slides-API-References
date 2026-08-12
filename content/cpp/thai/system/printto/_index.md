---
title: PrintTo()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.
type: docs
weight: 2146
url: /th/system/printto/
---
## System::PrintTo(DateTime, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(DateTime value, std::ostream *stream)
```

## System::PrintTo(DateTimeOffset, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(DateTimeOffset value, std::ostream *stream)
```

## System::PrintTo(const Decimal\&, ::std::ostream *) ฟังก์ชัน

เขียนค่าที่แสดงโดยออบเจ็กต์ที่ระบุไปยังสตรีมเอาต์พุตที่ระบุ.

```cpp
void System::PrintTo(const Decimal &d, ::std::ostream *os)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| d | const [Decimal](../decimal/)\& | อ็อบเจ็กต์ [Decimal](../decimal/) ที่จะพิมพ์ไปยังสตรีม |
| os | ::std::ostream * | สตรีมที่จะพิมพ์อ็อบเจ็กต์ที่ระบุไป |

## System::PrintTo(const Details_Exception\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(const Details_Exception &exception, std::ostream *stream)
```

## System::PrintTo(const ExceptionWrapper\<T\>\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
template<typename T> void System::PrintTo(const ExceptionWrapper<T> &exception_wrapper, std::ostream *stream)
```

## System::PrintTo(const Guid\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(const Guid &value, std::ostream *stream)
```

## System::PrintTo(const Nullable\<T\>\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
template<typename T> void System::PrintTo(const Nullable<T> &value, std::ostream *stream)
```

## System::PrintTo(const System::Object\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(const System::Object &value, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
template<typename T> std::enable_if_t<detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const SmartPtr\<T\>\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
template<typename T> std::enable_if_t<!detail::has_print_to_function<T>::value, void> System::PrintTo(const SmartPtr<T> &object_ptr, std::ostream *stream)
```

## System::PrintTo(const System::String\&, std::ostream *) ฟังก์ชัน

พิมพ์สตริงไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(const System::String &value, std::ostream *os)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | const [System::String](../string/)\& | เพื่อพิมพ์. |
| os | std::ostream * | ostream ปลายทาง. |

## System::PrintTo(TimeSpan, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
void System::PrintTo(TimeSpan value, std::ostream *stream)
```

## System::PrintTo(const WeakPtr\<T\>\&, std::ostream *) ฟังก์ชัน

พิมพ์ค่าไปยัง ostream. ส่วนใหญ่ใช้สำหรับการดีบัก.

```cpp
template<typename T> void System::PrintTo(const WeakPtr<T> &object_ptr, std::ostream *stream)
```

## ดูเพิ่มเติม

* คลาส [DateTime](../datetime/)
* คลาส [DateTimeOffset](../datetimeoffset/)
* คลาส [Decimal](../decimal/)
* คลาส [Details_Exception](../details_exception/)
* คลาส [ExceptionWrapper](../exceptionwrapper/)
* คลาส [Guid](../guid/)
* คลาส [Nullable](../nullable/)
* คลาส [Object](../object/)
* คลาส [SmartPtr](../smartptr/)
* คลาส [String](../string/)
* คลาส [TimeSpan](../timespan/)
* คลาส [WeakPtr](../weakptr/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)