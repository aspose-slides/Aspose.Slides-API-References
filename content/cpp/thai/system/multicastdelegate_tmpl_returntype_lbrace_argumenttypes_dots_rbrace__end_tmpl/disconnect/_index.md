---
title: disconnect()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลบ delegate ที่ระบุออกจากคอลเลกชันของ delegate
type: docs
weight: 170
url: /th/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) เมธอด

ลบ delegate ที่ระบุออกจากคอลเลกชันของ delegate

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| callback | [Callback](../callback/) | delegate ที่จะลบออกจากคอลเลกชัน |

### ค่าที่คืนกลับ

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) เมธอด

ลบเมธอดที่ไม่เป็น static ของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชันของ delegate

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| MemberType | ชนิดของเมธอดที่ไม่เป็น static ที่จะถูกลบออกจากคอลเลกชันของ delegate |
| ClassType | ชนิดของอ็อบเจ็กต์ที่เมธอดของมันจะถูกลบออกจากคอลเลกชันของ delegate |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| member | MemberType ClassType::* | พอยน์เตอร์ไปยังเมธอดที่ไม่เป็น static ของอ็อบเจ็กต์ที่ระบุ |
| obj | ClassType * | พอยน์เตอร์ไปยังอ็อบเจ็กต์ที่เมธอดของมันจะถูกลบออกจากคอลเลกชันของ delegate |

### ค่าที่คืนกลับ

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) เมธอด

ลบเมธอดที่ไม่เป็น static ของอ็อบเจ็กต์ที่ระบุออกจากคอลเลกชันของ delegate

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| MemberType | ชนิดของเมธอดที่ไม่เป็น static ที่จะถูกลบออกจากคอลเลกชันของ delegate |
| ClassType | ชนิดของอ็อบเจ็กต์ที่เมธอดของมันจะถูกลบออกจากคอลเลกชันของ delegate |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| member | MemberType ClassType::* | พอยน์เตอร์ไปยังเมธอดที่ไม่เป็น static ของอ็อบเจ็กต์ที่ระบุ |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | shared pointer ไปยังอ็อบเจ็กต์ที่เมธอดของมันจะถูกลบออกจากคอลเลกชันของ delegate |

### ค่าที่คืนกลับ

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) เมธอด

ลบอ็อบเจ็กต์ MulticastDelegate ที่ระบุออกจากคอลเลกชันของ delegate

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | อินสแตนซ์ของคลาส MulticastDelegate ที่จะลบออกจากคอลเลกชันของ delegate |

### ค่าที่คืนกลับ

อ้างอิงถึงตัวเอง

## ดูเพิ่มเติม

* ประเภทนิยาม [Callback](../callback/)
* ประเภทนิยาม [SharedPtr](../../sharedptr/)
* เมธอด [MulticastDelegate](../multicastdelegate/)
* คลาส [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)