---
title: SmartPtr()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างอ็อบเจ็กต์ SmartPtr ตามโหมดที่ต้องการ.
type: docs
weight: 1
url: /th/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) ตัวสร้าง

สร้าง [SmartPtr](../) วัตถุในโหมดที่ต้องการ.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) ตัวสร้าง

สร้าง [SmartPtr](../) พอยน์เตอร์ศูนย์ในโหมดที่ต้องการ.

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mode | std::nullptr_t | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) ตัวสร้าง

สร้าง [SmartPtr](../) ที่ชี้ไปยังอ็อบเจ็กต์ที่ระบุ หรือแปลงพอยน์เตอร์ดิบเป็น [SmartPtr](../).

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | พอยน์เตอร์ที่ชี้ไปยังอ็อบเจ็กต์. |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(const SmartPtr_&, SmartPtrMode) ตัวสร้าง

คัดลอกสร้าง [SmartPtr](../) วัตถุ. พอยน์เตอร์ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น.

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | พอยน์เตอร์ที่ต้องการคัดลอก. |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) ตัวสร้าง

คัดลอกสร้าง [SmartPtr](../) วัตถุ. พอยน์เตอร์ทั้งสองจะชี้ไปยังอ็อบเจ็กต์เดียวกันหลังจากนั้น. ทำการแปลงประเภทหากอนุญาต.

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Q | ประเภทของอ็อบเจ็กต์ที่ x ชี้ไป. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | พอยน์เตอร์ที่ต้องการคัดลอก. |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) ตัวสร้าง

ย้ายสร้าง [SmartPtr](../) วัตถุ. โดยทำการสลับพอยน์เตอร์สองตัว หากทั้งสองอยู่ในโหมดเดียวกัน. x อาจใช้ไม่ได้หลังจากเรียก.

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | พอยน์เตอร์ที่ต้องการย้าย. |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) ตัวสร้าง

แปลงประเภทของอาร์เรย์อ้างอิงโดยสร้างอาร์เรย์ใหม่ที่มีประเภทต่างกัน. มีประโยชน์เมื่อใน C# มีการคาสต์อาร์เรย์ที่ไม่รองรับใน C++.

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Y | ประเภทของอาร์เรย์ต้นฉบับ. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | พอยน์เตอร์ของอาร์เรย์ที่ต้องการสร้างสำเนา แต่มีประเภทของสมาชิกที่แตกต่างกัน. |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. |

## SmartPtr::SmartPtr(const Y\&) ตัวสร้าง

เริ่มต้นอาร์เรย์ว่าง. ใช้เพื่อแปลบางโครงสร้างโค้ด C#.

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| Y | ตัวแทนของประเภท EmptyArrayInitializer. |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) ตัวสร้าง

สร้าง [SmartPtr](../) ที่แชร์ข้อมูลความเป็นเจ้าของกับค่าเริ่มต้นของ ptr, แต่ถือพอยน์เตอร์ที่ไม่เกี่ยวข้องและไม่มีการจัดการ p.

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | พอยน์เตอร์อัจฉริยะอื่นที่จะแชร์ความเป็นเจ้าของจาก. |
| p | [Pointee_](../pointee_/) * | พอยน์เตอร์ที่ชี้ไปยังอ็อบเจ็กต์ที่ต้องจัดการ. |
| mode | [SmartPtrMode](../../smartptrmode/) | โหมดของพอยน์เตอร์. 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream"

// คลาสนี้มีฟิลด์ที่จะถูกพิมพ์ออก.
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// คลาสนี้มีอินสแตนซ์ของคลาส Foo.
class Bar : public System::Object
{
public:
  Foo data;
};

// ใช้เพื่อพิมพ์สตริงจากอินสแตนซ์ของคลาส Foo.
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// พิมพ์จำนวนของ shared pointer ที่ชี้ไปยังอ็อบเจ็กต์.
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // สร้าง SharedPtr ไปยังอินสแตนซ์ของคลาส Bar.
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // สร้าง SharedPtr ที่จะชี้ไปยังฟิลด์ของอินสแตนซ์คลาส Bar.
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // ทำให้พอยน์เตอร์ 'bar' ชี้ไปที่ nullptr.
  bar.reset();
  PrintSharedCount(bar);
  // bar->data ยังคงมีอยู่และพอยน์เตอร์ 'foo' ยังใช้ได้.
  PrintMessage(foo);

  return 0;
}
/*
โค้ดตัวอย่างนี้สร้างผลลัพธ์ต่อไปนี้:
จำนวนของ shared pointer: 1
จำนวนของ shared pointer: 2
จำนวนของ shared pointer: 0
สวัสดี, โลก!
*/
``` |

## See Also

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)