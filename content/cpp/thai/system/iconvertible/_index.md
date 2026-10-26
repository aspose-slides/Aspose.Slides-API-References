---
title: IConvertible
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดเมธอดที่แปลงค่าของอ้างอิงหรือประเภทค่าที่ทำงานเพื่อให้เป็นประเภท runtime ของภาษาโดยทั่วไปที่มีค่าที่เทียบเท่า อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันหรือข้อผิดพลาด assert ควรห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 937
url: /th/system/iconvertible/
---
## IConvertible คลาส

Defines methods that convert the value of the implementing reference or value type to a common language runtime type that has an equivalent value. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class IConvertible : public virtual System::Object
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อจุดประสงค์ภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นส่วนที่คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถทำแฮชอ็อบเจกต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/). |
| virtual [System::TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() | คืนค่ารหัสประเภทสำหรับอินสแตนซ์นี้. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) sentry. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าเคาน์เตอร์อ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์แม่แบบที่ n เป็นพอยน์เตอร์แบบอ่อน (แทนที่จะแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual **bool** [ToBoolean](./toboolean/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นค่า [Boolean](../boolean/) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **uint8_t** [ToByte](./tobyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็น uint32_teger 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual char_t [ToChar](./tochar/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นอักขระ Unicode ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual [System::DateTime](../datetime/) [ToDateTime](./todatetime/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็น [System::DateTime](../datetime/) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual [System::Decimal](../decimal/) [ToDecimal](./todecimal/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวน [System::Decimal](../decimal/) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **double** [ToDouble](./todouble/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวนจุดลอยแบบ double-precision ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **int16_t** [ToInt16](./toint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวนเต็มมีเครื่องหมาย 16 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **int32_t** [ToInt32](./toint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวนเต็มมีเครื่องหมาย 32 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **int64_t** [ToInt64](./toint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวนเต็มมีเครื่องหมาย 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **int8_t** [ToSByte](./tosbyte/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวนเต็มมีเครื่องหมาย 8 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **float** [ToSingle](./tosingle/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็นจำนวนจุดลอยแบบ single-precision ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual [System::String](../string/) [ToString](./tostring/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็น [System::String](../string/) ที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual [String](../string/) [ToString](./tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริงได้. |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [ToType](./totype/)(const [TypeInfo](../typeinfo/)\&, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็น [System::Object](../object/) ของ System::Type ที่ระบุซึ่งมีค่าที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **uint16_t** [ToUInt16](./touint16/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็น uint32_teger 16 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **uint32_t** [ToUInt32](./touint32/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่าของอินสแตนซ์นี้เป็น uint32_teger 32 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| virtual **uint64_t** [ToUInt64](./touint64/)([System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | แปลงค่ของอินสแตนซ์นี้เป็น uint32_teger 64 บิตที่เทียบเท่าโดยใช้ข้อมูลการจัดรูปแบบตามวัฒนธรรมที่ระบุ. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่ typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าเคาน์เตอร์อ้างอิงอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)