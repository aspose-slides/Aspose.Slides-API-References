---
title: Delegate()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คอนสตรัคเตอร์เริ่มต้น สร้างอ็อบเจ็กต์ delegate ที่ไม่ได้ชี้ไปที่ใดเลย.
type: docs
weight: 1
url: /th/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/delegate/
---
## Delegate< ReturnType(ArgumentTypes...)>::Delegate() เมธอด

คอนสตรัคเตอร์เริ่มต้น. สร้างอ็อบเจ็กต์ delegate ที่ไม่ได้ชี้ไปที่ใด ๆ.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate()=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(const Delegate\&) เมธอด




```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(Delegate\&&) เมธอด

คอนสตรัคเตอร์คัดลอกแบบเคลื่อนย้าย. ทำการถือครองเอนทิตี้ที่ถูกชี้โดย delegate ที่ระบุ.

```cpp
System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(Delegate &&o) noexcept
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| o | Delegate\&& | อ็อบเจ็กต์ Delegate ที่จะย้ายเอนทิตี้ที่ถูกชี้จากมัน |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) เมธอด

คอนสตรัคเตอร์. สร้างอ็อบเจ็กต์ delegate จากพอยน์เตอร์ที่ระบุไปยังฟังก์ชันอิสระหรือเมธอดสแตติก.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<!std::is_bind_expression<T>::value &&std::is_pointer<T>::value &&std::is_function<typename std::remove_pointer<T>::type>::value>::type *=0)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| The | ประเภทของพอยน์เตอร์ฟังก์ชันหรือเมธอดสแตติกที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| function | T | พอยน์เตอร์ไปยังฟังก์ชันหรือเมธอดสแตติกที่อินสแตนซ์ Delegate ที่สร้างขึ้นใหม่จะชี้ไป |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) เมธอด

คอนสตรัคเตอร์. สร้าง delegate จากพอยน์เตอร์ที่ระบุไปยังวัตถุฟังก์ชันที่สร้างโดย std::bind().

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(T function, typename std::enable_if<std::is_bind_expression<T>::value>::type *=0)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| The | ประเภทของวัตถุฟังก์ชันที่สร้างโดย std::bind() ที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| function | T | พอยน์เตอร์ไปยัง "bind expression" - พอยน์เตอร์ฟังก์ชันที่สร้างโดย std::bind() - ที่จะถูกชี้โดยอินสแตนซ์ Delegate ที่สร้างขึ้นใหม่ |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(int, T\&) เมธอด

คอนสตรัคเตอร์. สร้าง delegate จากวัตถุฟังก์ชันที่ระบุ.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(int functor_tag, T &functor)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของวัตถุฟังก์ชันที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functor_tag | int | ค่าตัวเลขเต็มเทียม; อาร์กิวเมนต์นี้ใช้เพื่อแก้ความกำกวม |
| functor | T\& | วัตถุฟังก์ชันที่ delegate ที่สร้างใหม่จะชี้ไป |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(long, T\&&) เมธอด

คอนสตรัคเตอร์แบบเคลื่อนย้าย. สร้าง delegate จากวัตถุฟังก์ชันที่ระบุ.

```cpp
template<class T> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(long functor_tag, T &&functor)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของวัตถุฟังก์ชันที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functor_tag | long | ค่าตัวเลขเต็มเทียม; อาร์กิวเมนต์นี้ใช้เพื่อแก้ความกำกวม |
| functor | T\&& | วัตถุฟังก์ชันที่ delegate ที่สร้างใหม่จะชี้ไป |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*, ClassType *) เมธอด

คอนสตรัคเตอร์. สร้าง delegate ที่ชี้ไปยังเมธอดที่ไม่ใช่สแตติกที่ระบุของอ็อบเจ็กต์ที่ระบุ.

```cpp
template<class MemberType,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType ClassType::*member, ClassType *obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| MemberType | ประเภทของเมธอดที่ไม่ใช่สแตติกที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |
| ClassType | ประเภทของอ็อบเจ็กต์ที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| member | MemberType ClassType::* | พอยน์เตอร์ไปยังเมธอดที่ไม่ใช่สแตติกที่ delegate ที่สร้างใหม่จะชี้ไป |
| obj | ClassType * | พอยน์เตอร์ไปยังเมธอดสมาชิกของอ็อบเจ็กต์ที่ delegate ที่สร้างใหม่จะชี้ไป |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*, const SharedPtr\<ClassType\>\&) เมธอด

คอนสตรัคเตอร์. สร้าง delegate ที่ชี้ไปยังเมธอดที่ไม่ใช่สแตติกที่ระบุของอ็อบเจ็กต์ที่ระบุ.

```cpp
template<class MemberType,class MemberClass,class ClassType> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(MemberType MemberClass::*member, const SharedPtr<ClassType> &obj)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| MemberType | ประเภทของเมธอดที่ไม่ใช่สแตติกที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |
| ClassType | ประเภทของอ็อบเจ็กต์ที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| member | MemberType MemberClass::* | พอยน์เตอร์ไปยังเมธอดที่ไม่ใช่สแตติกที่ delegate ที่สร้างใหม่จะชี้ไป |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | พอยน์เตอร์ SharedPtr คงที่ไปยังเมธอดสมาชิกของอ็อบเจ็กต์ที่ delegate ที่สร้างใหม่จะชี้ไป |

## Delegate< ReturnType(ArgumentTypes...)>::Delegate(std::function\<R(Args...)>) เมธอด

สร้างอ็อบเจ็กต์ delegate ที่ชี้ไปยังวัตถุฟังก์ชัน std::function.

```cpp
template<class R,class...> System::Delegate<ReturnType(ArgumentTypes...)>::Delegate(std::function<R(Args...)> f)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| R | ประเภทของค่าที่คืนจากวัตถุฟังก์ชันที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |
| Args | รายการอาร์กิวเมนต์ของวัตถุฟังก์ชันที่คอนสตรัคเตอร์ยอมรับเป็นอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| f | std::function\<R(Args...)> | วัตถุฟังก์ชันที่ delegate ที่สร้างใหม่จะชี้ไป |

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [Delegate< ReturnType(ArgumentTypes...)>](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)