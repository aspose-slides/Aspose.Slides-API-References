---
title: MediaTypeWithQualityHeaderValue
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "เป็นตัวแทนของ MIME type ที่มีปัจจัยคุณภาพเพิ่มเติมในค่าของหัวข้อ 'Content-Type' วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการอ้างอิงที่ผิดพลาด ให้ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 157
url: /th/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue คลาส


เป็นตัวแทนของ MIME type ที่มีปัจจัยคุณภาพเพิ่มเติมในค่าของหัวข้อ 'Content-Type' วัตถุของคลาสนี้ควรได้รับการจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลารันและ/หรือการอ้างอิงที่ผิดพลาด ให้ห่อหุ้มคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](../mediatypeheadervalue/equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ซึ่ง NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 แล้ว NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยของสไตล์ C# ที่ซึ่ง NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 แล้ว NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [String](../../system/string/) [get_CharSet](../mediatypeheadervalue/get_charset/)() | รับชุดอักขระ |
| [String](../../system/string/) [get_MediaType](../mediatypeheadervalue/get_mediatype/)() | รับค่าของหัวข้อ media-type |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](../mediatypeheadervalue/get_parameters/)() | คืนค่าพารามิเตอร์ของหัวข้อ media-type |
| [Nullable](../../system/nullable/)\<**double**\> [get_Quality](./get_quality/)() | รับค่าคุณภาพ |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เกี่ยวข้องกับอ็อบเจกต์ |
| **int32_t** [GetHashCode](../mediatypeheadervalue/gethashcode/)() const override | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้ทำการแฮชอ็อบเจกต์ที่กำหนดเองได้ |
| static **int32_t** [GetMediaTypeLength](../mediatypeheadervalue/getmediatypelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | แปลงสตริงที่ส่งเข้ามาตั้งแต่ตำแหน่งที่กำหนดเป็นอินสแตนซ์ของคลาส [MediaTypeHeaderValue](../mediatypeheadervalue/) |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
|  [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)() | สร้างอินสแตนซ์ใหม่ |
|  [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
|  [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | สร้างอินสแตนซ์ใหม่ |
|  [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
|  [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/), **double**) | สร้างอินสแตนซ์ใหม่ |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้ทำการคัดลอกชนิดที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้ทำการคัดลอกอะไรเลย จริงๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกของคลาสย่อยทำงานได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรเลย จริงๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกของคลาสย่อยทำงานได้ |
| static [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | แปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [MediaTypeWithQualityHeaderValue](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_CharSet](../mediatypeheadervalue/set_charset/)([String](../../system/string/)) | ตั้งค่าชุดอักขระ |
| void [set_MediaType](../mediatypeheadervalue/set_mediatype/)([String](../../system/string/)) | ตั้งค่าของหัวข้อ media-type |
| void [set_Quality](./set_quality/)([Nullable](../../system/nullable/)\<**double**\>) | ตั้งค่าคุณภาพ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| [String](../../system/string/) [ToString](../mediatypeheadervalue/tostring/)() const override | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยให้แปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [MediaTypeWithQualityHeaderValue](./) |
| static **bool** [TryParse](../mediatypeheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [MediaTypeHeaderValue](../mediatypeheadervalue/) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [MediaTypeHeaderValue](../mediatypeheadervalue/)
* เนมสเปซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)