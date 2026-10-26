---
title: Enum
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: ให้เมธอดที่ทำการดำเนินการบางอย่างบนค่าของประเภท enum นี้เป็นประเภทสแตติกที่ไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ
type: docs
weight: 1587
url: /th/system/enum/
---
## Enum struct

ให้บริการเมธอดที่ทำการดำเนินการบางอย่างบนค่าของประเภท enum นี้เป็นประเภทสแตติกซึ่งไม่มีบริการอินสแตนซ์ คุณไม่ควรสร้างอินสแตนซ์ของมันด้วยวิธีใดๆ

```cpp
template<class E,class Guard>class Enum
```

### Template parameters

| Parameter | Description |
| --- | --- |
| E | ประเภทของ enum ที่คลาสจัดการค่า |
| Guard | ประเภทของบริการที่มีวัตถุประสงค์เพื่อให้แน่ใจว่า **E** เป็นประเภทที่สามารถนับจำนวนได้ |

## Methods

| Method | Description |
| --- | --- |
| static int [Compare](./compare/)(E, T) | ทำการเปรียบเทียบเชิงคณิตศาสตร์ของค่าคงที่ของ enumeration ที่ระบุ |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetDescription](./getdescription/)(T) | คืนชื่อของค่าคงที่ของ enumeration ที่มีค่าเฉพาะที่กำหนด |
| static std::enable_if\<std::is_same\<T, E\>::value||std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, [String](../string/)\>::type [GetName](./getname/)(T) | คืนชื่อของค่าคงที่ของ enumeration ที่มีค่าเฉพาะที่กำหนด |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() | คืนอาเรย์ที่บรรจุชื่อของสมาชิกทั้งหมดของ enumeration **E** |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() | คืนประเภทพื้นฐานของ enumeration |
| static [ArrayPtr](../arrayptr/)\<E\> [GetValues](./getvalues/)() | คืนอาเรย์ที่บรรจุสมาชิกทั้งหมดของ enumeration **E** |
| static **bool** [HasFlag](./hasflag/)(E, E) | กำหนดว่าบิตที่ระบุถูกตั้งค่าในการแทนค่าแบบบิตารีของค่า enum ที่ระบุหรือไม่ |
| static **bool** [IsDefined](./isdefined/)(E) | กำหนดว่าค่าที่ระบุเป็นสมาชิกของประเภท enumeration **E** หรือไม่ |
| static std::enable_if\<std::is_convertible\<T, [UnderlyingType](./underlyingtype/)\>::value, **bool**\>::type [IsDefined](./isdefined/)(T) | กำหนดว่าค่าที่ระบุเป็นสมาชิกของประเภท enumeration **T** หรือไม่ |
| static **bool** [IsDefined](./isdefined/)(const [String](../string/)\&) | กำหนดว่าค่าที่มีชื่อที่ระบุอยู่ในสมาชิกของ enum **E** หรือไม่ |
| static E [Parse](./parse/)(const [String](../string/)\&, **bool**) | แปลงสตริงที่ระบุเป็นค่าคงที่ของ enum ที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, E\&) | พยายามแปลงสตริงที่ระบุเป็นค่าคงที่ของ enum ที่เทียบเท่า |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**, E\&) | พยายามแปลงสตริงที่ระบุเป็นค่าคงที่ของ enum ที่เทียบเท่า |

## Typedefs

| Typedef | Description |
| --- | --- |
| [UnderlyingType](./underlyingtype/) | นามแฝงสำหรับประเภทพื้นฐานของ enum |

## See Also

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)