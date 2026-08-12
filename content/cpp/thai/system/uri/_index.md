---
title: Uri
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "ตัวระบุทรัพยากรแบบสากล. วัตถุของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อขัดแย้งการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1392
url: /th/system/uri/
---
## คลาส Uri


Unified resource identifier. Objects of this class should only be allocated using [System::MakeObject()](../makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Uri : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static [UriHostNameType](../urihostnametype/) [CheckHostName](./checkhostname/)([String](../string/)) | กำหนดประเภทของชื่อโฮสต์ที่ระบุ |
| static **bool** [CheckSchemeName](./checkschemename/)(const [String](../string/)\&) | กำหนดว่าโครงสร้างที่ระบุเป็นค่าที่ถูกต้องหรือไม่ |
| static **int32_t** [Compare](./compare/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [UriComponents](../uricomponents/), [UriFormat](../uriformat/), [StringComparison](../stringcomparison/)) | เปรียบเทียบอ็อบเจ็กต์ [Uri](./) ที่ระบุโดยใช้กฎการเปรียบเทียบที่ระบุ |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override | กำหนดว่า URI ที่ออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุเป็นค่าเท่ากันหรือไม่ |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้เกณฑ์ของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ซึ่ง NaN สองค่าเป็นค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# ซึ่ง NaN สองค่าเป็นค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static [String](../string/) [EscapeDataString](./escapedatastring/)(const [String](../string/)\&) | แปลงสตริงเป็นรูปแบบที่เอสเคป |
| static [String](../string/) [EscapeUriString](./escapeuristring/)(const [String](../string/)\&) | แปลงสตริง URI เป็นรูปแบบที่เอสเคป |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| static **int32_t** [FromHex](./fromhex/)(char16_t) | รับค่าทศนิยมของตัวเลขฐานสิบหก |
| [String](../string/) [get_AbsolutePath](./get_absolutepath/)() const | ส่งคืนเส้นทางเต็มของ URI |
| [String](../string/) [get_AbsoluteUri](./get_absoluteuri/)() const | ส่งคืน URI ที่เป็นแบบเต็ม |
| [String](../string/) [get_Authority](./get_authority/)() const | ส่งคืนชื่อโฮสต์และหมายเลขพอร์ตของเซิร์ฟเวอร์ |
| [String](../string/) [get_DnsSafeHost](./get_dnssafehost/)() const | ส่งคืนชื่อโฮสต์ที่ไม่มีการเอสเคป |
| [String](../string/) [get_Fragment](./get_fragment/)() const | ส่งคืนส่วนที่เอสเคปของ URI |
| [String](../string/) [get_Host](./get_host/)() const | ส่งคืนชื่อโฮสต์ |
| [UriHostNameType](../urihostnametype/) [get_HostNameType](./get_hostnametype/)() const | ส่งคืนประเภทของชื่อโฮสต์ |
| [String](../string/) [get_IdnHost](./get_idnhost/)() const | ส่งคืนชื่อโดเมนสากลของโฮสต์ |
| **bool** [get_IsAbsoluteUri](./get_isabsoluteuri/)() const | กำหนดว่า URI ที่ออบเจ็กต์ปัจจุบันเป็นแบบเต็มหรือไม่ |
| **bool** [get_IsDefaultPort](./get_isdefaultport/)() const | กำหนดว่า URI ที่ออบเจ็กต์ปัจจุบันมีพอร์ตเริ่มต้นสำหรับโครงสร้างของ URI หรือไม่ |
| **bool** [get_IsFile](./get_isfile/)() const | กำหนดว่า URI ที่ออบเจ็กต์ปัจจุบันเป็นไฟล์หรือไม่ |
| **bool** [get_IsLoopback](./get_isloopback/)() const | กำหนดว่า URI ที่ออบเจ็กต์ปัจจุบันอ้างอิงถึงโฮสต์ท้องถิ่นหรือไม่ |
| **bool** [get_IsUnc](./get_isunc/)() const | กำหนดว่า URI ที่ออบเจ็กต์ปัจจุบันเป็นพาธ UNC หรือไม่ |
| [String](../string/) [get_LocalPath](./get_localpath/)() const | ส่งคืนการแสดงผลของระบบปฏิบัติการของชื่อไฟล์ที่ URI ที่ออบเจ็กต์ปัจจุบันอ้างอิง |
| [String](../string/) [get_OriginalString](./get_originalstring/)() const | ส่งคืนสตริง URI ที่ส่งให้คอนสตรัคเตอร์เมื่อออบเจ็กต์นี้ถูกสร้าง |
| [String](../string/) [get_PathAndQuery](./get_pathandquery/)() const | ส่งคืนส่วนของเส้นทางเต็มและคิวรีของ URI ที่ออบเจ็กต์ปัจจุบัน แยกโดยเครื่องหมายคำถาม (?) |
| **int32_t** [get_Port](./get_port/)() const | ส่งคืนหมายเลขพอร์ตของ URI ที่ออบเจ็กต์ปัจจุบัน |
| [String](../string/) [get_Query](./get_query/)() const | ส่งคืนข้อมูลคิวรีที่รวมอยู่ใน URI ที่ออบเจ็กต์ปัจจุบัน |
| [String](../string/) [get_Scheme](./get_scheme/)() const | ส่งคืนโครงสร้างของ URI ที่ออบเจ็กต์ปัจจุบัน |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [get_Segments](./get_segments/)() const | ส่งคืนอาร์เรย์ของสตริงที่ประกอบด้วยส่วนของเส้นทางของ URI ที่ออบเจ็กต์ปัจจุบัน |
| **bool** [get_UserEscaped](./get_userescaped/)() const | กำหนดว่าสตริง URI ที่ส่งให้คอนสตรัคเตอร์ของออบเจ็กต์นี้ถูกเอสเคปอย่างสมบูรณ์หรือไม่ |
| [String](../string/) [get_UserInfo](./get_userinfo/)() const | ส่งคืนชื่อผู้ใช้, รหัสผ่าน และข้อมูลผู้ใช้อื่น ๆ ที่เกี่ยวข้องกับ URI ที่ออบเจ็กต์ปัจจุบัน |
| [String](../string/) [GetComponents](./getcomponents/)([UriComponents](../uricomponents/), [UriFormat](../uriformat/)) const | ส่งคืนส่วนประกอบที่ระบุของ URI ที่ออบเจ็กต์ปัจจุบันโดยใช้การเอสเคปที่ระบุ |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | รับค่าแฮชโค้ดของ URI |
| [String](../string/) [GetLeftPart](./getleftpart/)([UriPartial](../uripartial/)) | ส่งคืนส่วนที่ระบุของ URI ที่ออบเจ็กต์ปัจจุบัน |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../object/gettype/) |
| static [String](../string/) [HexEscape](./hexescape/)(char16_t) | ส่งคืนค่าเลขฐานสิบหกที่เทียบเท่ากับอักขระที่ระบุ |
| static char16_t [HexUnescape](./hexunescape/)(const [String](../string/)\&, **int32_t**\&) | แปลงตัวแทนเลขฐานสิบหกของอักขระที่ระบุเป็นอักขระ |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบายหรือไม่. คล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| **bool** [IsBaseOf](./isbaseof/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) const | กำหนดว่า URI ที่ออบเจ็กต์ [Uri](./) ปัจจุบันเป็นฐานของ URI ที่ออบเจ็กต์ [Uri](./) ระบุหรือไม่ |
| static **bool** [IsHexDigit](./ishexdigit/)(char16_t) | กำหนดว่าอักขระที่ระบุเป็นตัวเลขฐานสิบหกที่ถูกต้องหรือไม่ |
| static **bool** [IsHexEncoding](./ishexencoding/)(const [String](../string/)\&, **int32_t**) | กำหนดว่าตัวอักษรในสตริงที่ระบุที่ตำแหน่งที่ระบุเป็นการเข้ารหัสฐานสิบหกหรือไม่ |
| **bool** [IsWellFormedOriginalString](./iswellformedoriginalstring/)() const | บ่งบอกว่าสตริงที่ใช้สร้าง [Uri](./) นี้มีรูปแบบที่ถูกต้องและไม่จำเป็นต้องเอสเคปเพิ่มเติม |
| static **bool** [IsWellFormedUriString](./iswellformeduristring/)(const [String](../string/)\&, [UriKind](../urikind/)) | กำหนดว่าสตริงที่ระบุเป็น URI ที่รูปแบบถูกต้องหรือไม่ |
| void [Lock](../object/lock/)() | ทำงานเหมือนคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) |
| [String](../string/) [MakeRelative](./makerelative/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | กำหนดความแตกต่างระหว่างสองอินสแตนซ์ของ [Uri](./) |
| [SharedPtr](../sharedptr/)\<[Uri](./)\> [MakeRelativeUri](./makerelativeuri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | กำหนดความแตกต่างระหว่าง URI ที่ออบเจ็กต์ปัจจุบันและออบเจ็กต์ [Uri](./) ที่ระบุ |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายเมธอด [Object.MemberwiseClone()](../object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบออบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| [String](../string/) [ToString](./tostring/)() const override | ส่งคืนการแสดงผลเป็นสตริงของ URI ที่ออบเจ็กต์ปัจจุบัน |
| static **bool** [TryCreate](./trycreate/)(const [String](../string/)\&, [UriKind](../urikind/), [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | สร้างออบเจ็กต์ [Uri](./) ที่แสดง URI ที่ระบุ; อาร์กิวเมนต์ระบุชนิดของ URI |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | สร้างออบเจ็กต์ [Uri](./) จากออบเจ็กต์ [Uri](./) ที่ระบุซึ่งเป็น URI พื้นฐานและสตริงของ URI เชิงสัมพันธ์ |
| static **bool** [TryCreate](./trycreate/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | สร้างออบเจ็กต์ [Uri](./) จาก URI พื้นฐานและเชิงสัมพันธ์ที่ระบุ |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำงานคล้าย typeof([System.Object](../object/)) ของ C# |
| static [String](../string/) [UnescapeDataString](./unescapedatastring/)(const [String](../string/)\&) | ยกเลิกการเอสเคปสตริงที่ระบุ |
| void [Unlock](../object/unlock/)() | ทำงานคล้ายคำสั่ง lock() ของ C# ที่ปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../lockcontext/) |
|  [Uri](./uri/)(const [String](../string/)\&) | สร้างออบเจ็กต์ [Uri](./) ที่แสดง URI ที่ระบุ |
|  [Uri](./uri/)(const [String](../string/)\&, **bool**) | สร้างออบเจ็กต์ [Uri](./) ที่แสดง URI ที่ระบุ; อาร์กิวเมนต์ระบุว่า URI ควรเอสเคปหรือไม่ |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&, **bool**) | สร้างออบเจ็กต์ [Uri](./) จากออบเจ็กต์ [Uri](./) ที่ระบุซึ่งเป็น URI พื้นฐานและสตริง URI เชิงสัมพันธ์; อาร์กิวเมนต์ระบุว่า URI ควรเอสเคปหรือไม่ |
|  [Uri](./uri/)(const [String](../string/)\&, [UriKind](../urikind/)) | สร้างออบเจ็กต์ [Uri](./) ที่แสดง URI ที่ระบุ; อาร์กิวเมนต์ระบุชนิดของ URI |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [String](../string/)\&) | สร้างออบเจ็กต์ [Uri](./) จาก URI พื้นฐานและเชิงสัมพันธ์ที่ระบุ |
|  [Uri](./uri/)(const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&, const [SharedPtr](../sharedptr/)\<[Uri](./)\>\&) | สร้างออบเจ็กต์ [Uri](./) จาก URI พื้นฐานและเชิงสัมพันธ์ที่ระบุ |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [SchemeDelimiter](./schemedelimiter/) | ระบุอักขระที่แยกโครงสร้างโปรโตคอลการสื่อสารจากส่วนที่อยู่ของ [Uri](./) |
| static [UriSchemeFile](./urischemefile/) | ระบุว่า [Uri](./) เป็นพอยน์เตอร์ไปยังไฟล์ |
| static [UriSchemeFtp](./urischemeftp/) | ระบุว่า [Uri](./) ถูกเข้าถึงผ่าน File Transfer Protocol |
| static [UriSchemeGopher](./urischemegopher/) | ระบุว่า [Uri](./) ถูกเข้าถึงผ่านโปรโตคอล Gopher |
| static [UriSchemeHttp](./urischemehttp/) | ระบุว่า [Uri](./) ถูกเข้าถึงผ่าน Hypertext Transfer Protocol |
| static [UriSchemeHttps](./urischemehttps/) | ระบุว่า [Uri](./) ถูกเข้าถึงผ่าน Secure Hypertext Transfer Protocol |
| static [UriSchemeMailto](./urischememailto/) | ระบุว่า [Uri](./) เป็นที่อยู่อีเมลและถูกเข้าถึงผ่าน Simple Mail Transport Protocol |
| static [UriSchemeNetPipe](./urischemenetpipe/) | ระบุว่า [Uri](./) ถูกเข้าถึงผ่านโครงการ NetPipe ของ [Windows](../../system.windows/) Communication Foundation |
| static [UriSchemeNetTcp](./urischemenettcp/) | ระบุว่า [Uri](./) ถูกเข้าถึงผ่านโครงการ NetTcp ของ [Windows](../../system.windows/) Communication Foundation |
| static [UriSchemeNews](./urischemenews/) | ระบุว่า [Uri](./) เป็นกลุ่มข่าวอินเทอร์เน็ตและถูกเข้าถึงผ่าน Network News Transport Protocol |
| static [UriSchemeNntp](./urischemenntp/) | ระบุว่า [Uri](./) เป็นกลุ่มข่าวอินเทอร์เน็ตและถูกเข้าถึงผ่าน Network News Transport Protocol |

## หมายเหตุ



```cpp
#include "system/smart_ptr.h"
#include "system/uri.h"
#include <iostream>

int main()
{
  const auto uri = System::MakeObject<System::Uri>(u"https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/");

std::cout <<
  "AbsolutePath: " << uri->get_AbsolutePath() << std::endl <<
  "AbsoluteUri: " << uri->get_AbsoluteUri() << std::endl <<
  "Authority: " << uri->get_Authority() << std::endl <<
  "DnsSafeHost: " << uri->get_DnsSafeHost() << std::endl <<
  "Fragment: " << uri->get_Fragment() << std::endl <<
  "Host: " << uri->get_Host() << std::endl <<
  "IdnHost: " << uri->get_IdnHost() << std::endl <<
  "LocalPath: " << uri->get_LocalPath() << std::endl <<
  "OriginalString: " << uri->get_OriginalString() << std::endl <<
  "PathAndQuery: " << uri->get_PathAndQuery() << std::endl <<
  "Port: " << uri->get_Port() << std::endl <<
  "Query: " << uri->get_Query() << std::endl <<
  "Scheme: " << uri->get_Scheme() << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ดังต่อไปนี้:
AbsolutePath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
AbsoluteUri: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Authority: docs.codeporting.com
DnsSafeHost: docs.codeporting.com
Fragment:
Host: docs.codeporting.com
IdnHost: docs.codeporting.com
LocalPath: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
OriginalString: https://docs.codeporting.com/translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
PathAndQuery: /translator/cs2cpp/release-notes/2021/codeporting-translator-cs2cpp-21-9/
Port: 443
Query:
Scheme: https
*/
```

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)