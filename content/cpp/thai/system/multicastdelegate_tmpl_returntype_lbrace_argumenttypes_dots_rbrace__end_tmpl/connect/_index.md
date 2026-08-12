---
title: connect()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เพิ่ม delegate ที่ระบุลงในคอลเลกชัน.
type: docs
weight: 144
url: /th/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) เมธอด


เพิ่ม delegate ที่ระบุลงในคอลเลกชัน

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | delegate ที่จะเพิ่มลงในคอลเลกชัน |

### Return Value

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) เมธอด


เพิ่มฟังก์ชันอ็อบเจกต์ที่ระบุลงในคอลเลกชันของ delegate ฟังก์ชันอ็อบเจกต์จะถูกแปลงเป็นประเภท delegate Callback ก่อนจะถูกเพิ่มลงในคอลเลกชัน

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| R | ประเภทค่าที่คืนของฟังก์ชันอ็อบเจกต์ที่ต้องการเพิ่มลงในคอลเลกชัน |
| Args | รายการอาร์กิวเมนต์ของฟังก์ชันอ็อบเจกต์ที่ต้องการเพิ่มลงในคอลเลกชัน |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | ฟังก์ชันอ็อบเจกต์ที่ต้องการเพิ่มลงในคอลเลกชัน |

### Return Value

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) เมธอด


เพิ่มอ็อบเจกต์ MulticastDelegate ที่ระบุลงในคอลเลกชันของ delegate

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | อินสแตนซ์ของคลาส MulticastDelegate ที่ต้องการเพิ่มลงในคอลเลกชันของ delegate |

### Return Value

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) เมธอด


เพิ่มเมธอด non-static ที่ระบุของอ็อบเจกต์ที่ระบุลงในคอลเลกชันของ delegate

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | ประเภทของเมธอด non-static ที่จะเพิ่มลงในคอลเลกชันของ delegate |
| ClassType | ประเภทของอ็อบเจกต์ที่เมธอดของมันจะถูกเพิ่มลงในคอลเลกชัน |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | ตัวชี้ไปยังเมธอด non-static ของอ็อบเจกต์ที่ระบุ |
| obj | ClassType * | ตัวชี้ไปยังอ็อบเจกต์ที่เมธอดของมันจะถูกเพิ่มลงในคอลเลกชันของ delegate |

### Return Value

อ้างอิงถึงตัวเอง

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) เมธอด


เพิ่มเมธอด non-static ที่ระบุของอ็อบเจกต์ที่ระบุลงในคอลเลกชันของ delegate

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | ประเภทของเมธอด non-static ที่จะเพิ่มลงในคอลเลกชันของ delegate |
| ClassType | ประเภทของอ็อบเจกต์ที่เมธอดของมันจะถูกเพิ่มลงในคอลเลกชันของ delegate |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | ตัวชี้ไปยังเมธอด non-static ของอ็อบเจกต์ที่ระบุ |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | shared pointer ไปยังอ็อบเจกต์ที่เมธอดของมันจะถูกเพิ่มลงในคอลเลกชันของ delegate |

### Return Value

อ้างอิงถึงตัวเอง

## See Also

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)