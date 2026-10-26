---
title: MulticastDelegate()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างคอลเลกชันเปล่า.
type: docs
weight: 1
url: /th/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() เมธอด

สร้างคอลเลกชันเปล่า

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) เมธอด

เทียบเท่ากับคอนสตรัคเตอร์เริ่มต้น

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) เมธอด

ทำการคัดลอกเชโลของคอลเลกชัน delegate

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| o | const MulticastDelegate\& | อินสแตนซ์ของคลาส MulticastDelegate เพื่อคัดลอกคอลเลกชันของ delegate จาก |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) เมธอด

คอนสตรัคเตอร์การย้าย

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| o | MulticastDelegate\&& | อินสแตนซ์ของคลาส MulticastDelegate เพื่อย้ายคอลเลกชันของ delegate จาก |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) เมธอด

สร้างอินสแตนซ์และใส่ delegate ที่ระบุลงในคอลเลกชัน delegate

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | delegate ที่จะใส่ลงในคอลเลกชัน delegate |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) เมธอด

สร้างอินสแตนซ์และใส่ค่าที่ระบุลงในคอลเลกชัน delegate

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของค่าที่จะใส่ลงในคอลเลกชัน delegate ของอินสแตนซ์ที่สร้างใหม่; ชนิดต้องสามารถแปลงเป็นชนิด Callback ได้ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arg | T | ค่าที่จะใส่ลงในคอลเลกชัน delegate |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) เมธอด

สร้างอินสแตนซ์และใส่ค่าที่ระบุลงในคอลเลกชัน delegate

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | ค่าที่จะใส่ลงในคอลเลกชัน delegate |

## ดูเพิ่มเติม

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)