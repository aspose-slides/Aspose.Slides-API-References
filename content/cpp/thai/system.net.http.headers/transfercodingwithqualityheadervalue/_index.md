---
title: TransferCodingWithQualityHeaderValue
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "แสดงค่าที่มีคุณภาพเพิ่มเติมของส่วนหัว 'Accept-Encoding' ออบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้และ/หรือความผิดพลาดของการตรวจสอบเงื่อนไข. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 313
url: /th/system.net.http.headers/transfercodingwithqualityheadervalue/
---
## TransferCodingWithQualityHeaderValue คลาส

Represents a value with an additional quality of the 'Accept-Encoding' header. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TransferCodingWithQualityHeaderValue : public System::Net::Http::Headers::TransferCodingHeaderValue
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| **bool** [Equals](../transfercodingheadervalue/equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบอ็อบเจ็กต์โดยใช้ C# [Object.Equals](../../system/object/equals/) semantics. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](../transfercodingheadervalue/get_parameters/)() | คืนค่าพารามิเตอร์. |
| [Nullable](../../system/nullable/)\<**double**\> [get_Quality](./get_quality/)() | รับค่าคุณภาพของส่วนหัว 'Accept-Encoding'. |
| [String](../../system/string/) [get_Value](../transfercodingheadervalue/get_value/)() | คืนค่าหนึ่งค่า. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| **int32_t** [GetHashCode](../transfercodingheadervalue/gethashcode/)() const override | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| static **int32_t** [GetTransferCodingLength](../transfercodingheadervalue/gettransfercodinglength/)([String](../../system/string/), **int32_t**, const [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\>\&, [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\&) | แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [TransferCodingHeaderValue](../transfercodingheadervalue/). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เป็นอเนกประสงค์ของโอเปอเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริงๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingWithQualityHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | แปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [TransferCodingWithQualityHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [set_Quality](./set_quality/)([Nullable](../../system/nullable/)\<**double**\>) | ตั้งค่าคุณภาพของส่วนหัว 'Accept-Encoding'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](../transfercodingheadervalue/tostring/)() const override | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
|  [TransferCodingHeaderValue](../transfercodingheadervalue/transfercodingheadervalue/)() | สร้างอินสแตนซ์ใหม่. |
|  [TransferCodingHeaderValue](../transfercodingheadervalue/transfercodingheadervalue/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
|  [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)() | สร้างอินสแตนซ์ใหม่. |
|  [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่. |
|  [TransferCodingWithQualityHeaderValue](./transfercodingwithqualityheadervalue/)([String](../../system/string/), **double**) | สร้างอินสแตนซ์ใหม่. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingWithQualityHeaderValue](./)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [TransferCodingWithQualityHeaderValue](./). |
| static **bool** [TryParse](../transfercodingheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](../transfercodingheadervalue/)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [TransferCodingHeaderValue](../transfercodingheadervalue/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ของ C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [TransferCodingHeaderValue](../transfercodingheadervalue/)
* เนมสเปซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)