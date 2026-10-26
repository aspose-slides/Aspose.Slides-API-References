---
title: Cookie
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงคุกกี้ HTTP. วัตถุของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตคหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ไว้ในพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1
url: /th/system.net/cookie/
---
## Cookie คลาส

แสดงถึงคุกกี้ HTTP. วัตถุของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตคหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ไว้ในตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class Cookie : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | สร้างสำเนาของอินสแตนซ์ปัจจุบัน |
| [Cookie](./cookie/)() | สร้างอินสแตนซ์ใหม่ |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
| [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | สร้างอินสแตนซ์ใหม่ |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุชนิดอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | ดึงค่าของแอตทริบิวต์ 'Comment' |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | ดึงค่าของแอตทริบิวต์ 'CommentURL' |
| **bool** [get_Discard](./get_discard/)() const | ดึงค่าของแอตทริบิวต์ 'Discard' |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | ดึงค่าของแอตทริบิวต์ 'Domain' |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | ดึงค่าที่บ่งชี้ว่าดอมเมนเป็นแบบโดยนัยหรือไม่ |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | คืนค่ากุญแจโดเมน |
| **bool** [get_Expired](./get_expired/)() | ดึงค่าที่บ่งชี้ว่าคุกกี้หมดอายุหรือไม่ |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | ดึงค่าของแอตทริบิวต์ 'Expires' |
| **bool** [get_HttpOnly](./get_httponly/)() const | ดึงค่ของแอตทริบิวต์ 'HttpOnly' |
| [String](../../system/string/) [get_Name](./get_name/)() const | ดึงชื่อคุกกี้ |
| [String](../../system/string/) [get_Path](./get_path/)() const | ดึงค่าของแอตทริบิวต์ 'Path' |
| **bool** [get_Plain](./get_plain/)() const | คืนค่าที่บ่งชี้ว่าข้อกำหนดคุกกี้เป็น 'Plain' หรือไม่ |
| [String](../../system/string/) [get_Port](./get_port/)() const | ดึงค่าของแอตทริบิวต์ 'Port' |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | คืนคอลเลกชันของค่าของแอตทริบิวต์ 'Port' |
| **bool** [get_Secure](./get_secure/)() const | ดึงค่าของแอตทริบิวต์ 'Secure' |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | คืนเวลาเมื่อคุกกี้ถูกสร้าง |
| [String](../../system/string/) [get_Value](./get_value/)() const | ดึงค่าของคุกกี้ |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | ดึงข้อกำหนดของคุกกี้ |
| **int32_t** [get_Version](./get_version/)() const | ดึงค่าของแอตทริบิวต์ '[Version](../../system/version/)' |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | อเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถสร้างแฮชของวัตถุที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของวัตถุ. อเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | เมธอดนี้ถูกเรียกโดยเมธอดอื่นเพื่อกำหนดชื่อเมธอด |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อเนกประสงค์ของตัวดำเนินการ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของคลาสตรุษ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของคลาสตรุษ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจกต์ชนิดค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | ตั้งค่าของแอตทริบิวต์ 'Comment' |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | ตั้งค่าของแอตทริบิวต์ 'CommentURL' |
| void [set_Discard](./set_discard/)(**bool**) | ตั้งค่าของแอตทริบิวต์ 'Discard' |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | ตั้งค่าของแอตทริบิวต์ 'Domain' |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าดอมเมนเป็นแบบโดยนัยหรือไม่ |
| void [set_Expired](./set_expired/)(**bool**) | ตั้งค่าที่บ่งชี้ว่าคุกกี้หมดอายุหรือไม่ |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | ตั้งค่าของแอตทริบิวต์ 'Expires' |
| void [set_HttpOnly](./set_httponly/)(**bool**) | ตั้งค่าของแอตทริบิวต์ 'HttpOnly' |
| void [set_Name](./set_name/)([String](../../system/string/)) | ตั้งชื่อคุกกี้ |
| void [set_Path](./set_path/)([String](../../system/string/)) | ตั้งค่าของแอตทริบิวต์ 'Path' |
| void [set_Port](./set_port/)([String](../../system/string/)) | ตั้งค่าของแอตทริบิวต์ 'Port' |
| void [set_Secure](./set_secure/)(**bool**) | ตั้งค่าของแอตทริบิวต์ 'Secure' |
| void [set_Value](./set_value/)([String](../../system/string/)) | ตั้งค่าคุกกี้ |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | ตั้งค่าข้อกำหนดของคุกกี้ |
| void [set_Version](./set_version/)(**int32_t**) | ตั้งค่าของแอตทริบิวต์ '[Version](../../system/version/)' |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | ทำการซีเรียลไลซ์อินสแตนซ์ปัจจุบันเป็นสตริง |
| [String](../../system/string/) [ToString](./tostring/)() const override | อเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้แปลงอ็อบเจกต์ที่กำหนดเองเป็นสtringได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | ตรวจสอบและตั้งค่าของแอตทริบิวต์เริ่มต้น |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | ชื่อแอตทริบิวต์ 'Comment' |
| static [CommentUrlAttributeName](./commenturlattributename/) | ชื่อแอตทริบิวต์ 'CommentURL' |
| static [DiscardAttributeName](./discardattributename/) | ชื่อแอตทริบิวต์ 'Discard' |
| static [DomainAttributeName](./domainattributename/) | ชื่อแอตทริบิวต์ 'Domain' |
| static [EqualsLiteral](./equalsliteral/) | ตัวคั่นที่ใช้แยกชื่อและค่าของแอตทริบิวต์ |
| static [ExpiresAttributeName](./expiresattributename/) | ชื่อแอตทริบิวต์ 'Expires' |
| static [HttpOnlyAttributeName](./httponlyattributename/) | ชื่อแอตทริบิวต์ 'HttpOnly' |
| static [MaxAgeAttributeName](./maxageattributename/) | ชื่อแอตทริบิวต์ 'Max-Age' |
| static [MaxSupportedVersion](./maxsupportedversion/) | รุ่นที่สนับสนุนสูงสุด |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | รูปแบบสตริงของรุ่นที่สนับสนุนสูงสุด |
| static [PathAttributeName](./pathattributename/) | ชื่อแอตทริบิวต์ 'Path' |
| static [PortAttributeName](./portattributename/) | ชื่อแอตทริบิวต์ 'Port' |
| static [PortSplitDelimiters](./portsplitdelimiters/) | อาร์เรย์ที่มีตัวคั่นสำหรับค่าของแอตทริบิวต์ 'Port' |
| static [QuotesLiteral](./quotesliteral/) | สัญลักษณ์ที่ใช้หุ้มส่วนของแอตทริบิวต์ |
| static [ReservedToName](./reservedtoname/) | ค่าที่สงวนไว้สำหรับชื่อคุกกี้ |
| static [ReservedToValue](./reservedtovalue/) | ค่าที่สงวนไว้สำหรับค่าคุกกี้ |
| static [SecureAttributeName](./secureattributename/) | ชื่อแอตทริบิวต์ 'Secure' |
| static [SeparatorLiteral](./separatorliteral/) | ตัวคั่นของแอตทริบิวต์ |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | คำนำหน้าของชื่อแอตทริบิวต์พิเศษ |
| static [VersionAttributeName](./versionattributename/) | ชื่อแอตทริบิวต์ '[Version](../../system/version/)' |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Net](../)
* ไลบรารี [Aspose.Slides](../../)