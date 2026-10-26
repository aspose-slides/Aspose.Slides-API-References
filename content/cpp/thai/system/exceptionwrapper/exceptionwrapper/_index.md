---
title: ExceptionWrapper()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: สร้างอินสแตนซ์ null ของคลาส ExceptionWrapper ที่ไม่เป็นตัวแทนของข้อยกเว้นใด ๆ
type: docs
weight: 14
url: /th/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor

สร้างอินสแตนซ์ null ของคลาส [ExceptionWrapper](../) ที่ไม่เป็นตัวแทนของข้อยกเว้นใด ๆ

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) constructor

สร้างอินสแตนซ์ของคลาส [ExceptionWrapper](../) ที่มีตัวชี้ที่ถูกส่งเข้ามา

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | ตัวชี้อัจฉริยะไปยังอินสแตนซ์ของคลาส Exception |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) constructor

คอนสตรักเตอร์สำเนา

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | อินสแตนซ์อื่นของคลาส wrapper ที่ต้องทำสำเนา |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) constructor

คอนสตรักเตอร์ย้าย

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | อินสแตนซ์อื่นของคลาส wrapper ที่ต้องย้าย |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor

คอนสตรักเตอร์ที่ส่งต่อพารามิเตอร์ไปยังคอนสตรักเตอร์ของคลาส Exception และสร้างตัวชี้อัจฉริยะที่เก็บอินสแตนซ์ใหม่ของคลาส Exception

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## See Also

* Typedef [ExceptionPtr](../../exceptionptr/)
* คลาส [ExceptionWrapper](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)