---
title: CultureInfo
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คอลเลกชันของค่าที่กำหนดตามวัฒนธรรมและอัลกอริทึม. การตั้งค่าจะเปิดใช้งานเฉพาะกับอ็อบเจ็กต์ที่ไม่ได้เป็นแบบอ่านอย่างเดียว. อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการละเมิดการยืนยัน. ควรห่อคลาสนี้ด้วยตัวชี้ System::SmartPtr เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน."
type: docs
weight: 53
url: /th/system.globalization/cultureinfo/
---
## CultureInfo คลาส

คอลเลกชันของค่าที่กำหนดตามวัฒนธรรมและอัลกอริทึม. การตั้งค่าจะเปิดใช้งานเฉพาะกับอ็อบเจ็กต์ที่ไม่ได้เป็นแบบอ่านอย่างเดียว. อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือการละเมิดการยืนยัน. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) เสมอและใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอาร์กิวเมนต์ให้ฟังก์ชัน.

```cpp
class CultureInfo : public virtual System::Object,
                    public System::IFormatProvider,
                    public System::ICloneable
```

## วิธีการ

| Method | Description |
| --- | --- |
| void [ClearCachedData](./clearcacheddata/)() | รีเฟรชข้อมูลวัฒนธรรมที่เก็บไว้ในแคช. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | ทำสำเนาคลอนของข้อมูลวัฒนธรรม. |
| static [CultureInfoPtr](../cultureinfoptr/) [CreateSpecificCulture](./createspecificculture/)(const [String](../../system/string/)\&) | สร้างวัฒนธรรมตามชื่อ. |
| explicit  [CultureInfo](./cultureinfo/)(int) | ข้อมูล RTTI. |
|  [CultureInfo](./cultureinfo/)(int, **bool**) | คอนสตรัคเตอร์. |
| explicit  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&) | คอนสตรัคเตอร์. |
|  [CultureInfo](./cultureinfo/)(const [String](../../system/string/)\&, **bool**) | คอนสตรัคเตอร์. |
|  [CultureInfo](./cultureinfo/)(std::nullptr_t) | จะโยน ArgumentNullException เสมอ. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบวัตถุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมทั้ง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating pointของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมทั้ง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น. |
| virtual [CalendarPtr](../calendarptr/) [get_Calendar](./get_calendar/)() const | ดึงปฏิทินที่ใช้โดยวัฒนธรรม. |
| virtual [CompareInfoPtr](../compareinfoptr/) [get_CompareInfo](./get_compareinfo/)() const | ดึงตัวเปรียบเทียบสตริงที่สอดคล้องกับกฎของวัฒนธรรม. |
| [CultureTypes](../culturetypes/) [get_CultureTypes](./get_culturetypes/)() const | ดึงบิตคู่ของประเภทวัฒนธรรมที่อธิบายวัฒนธรรมปัจจุบัน. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentCulture](./get_currentculture/)() | ดึงชุดวัฒนธรรมของเธรดปัจจุบัน. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_CurrentUICulture](./get_currentuiculture/)() | ดึงวัฒนธรรม UI ของเธรดปัจจุบัน. |
| virtual [DateTimeFormatInfoPtr](../datetimeformatinfoptr/) [get_DateTimeFormat](./get_datetimeformat/)() const | ดึงข้อมูลรูปแบบวันที่. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentCulture](./get_defaultthreadcurrentculture/)() | ดึงวัฒนธรรมค่าเริ่มต้นในโดเมนแอปพลิเคชันปัจจุบัน. |
| static [CultureInfoPtr](../cultureinfoptr/) [get_DefaultThreadCurrentUICulture](./get_defaultthreadcurrentuiculture/)() | ดึงวัฒนธรรม UI ค่าเริ่มต้นในโดเมนแอปพลิเคชันปัจจุบัน. |
| virtual [String](../../system/string/) [get_DisplayName](./get_displayname/)() const | ดึงชื่อที่แสดงของวัฒนธรรม. |
| virtual [String](../../system/string/) [get_EnglishName](./get_englishname/)() const | ดึงชื่อภาษาอังกฤษของวัฒนธรรม. |
| [String](../../system/string/) [get_IetfLanguageTag](./get_ietflanguagetag/)() const | ดึงชื่อ RFC 4646 สำหรับภาษาหนึ่ง. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InstalledUICulture](./get_installeduiculture/)() | ดึงวัฒนธรรมที่ติดตั้งมาพร้อมระบบปฏิบัติการ. |
| static const [CultureInfoPtr](../cultureinfoptr/)\& [get_InvariantCulture](./get_invariantculture/)() | ดึงวัฒนธรรมที่คงที่. |
| virtual **bool** [get_IsNeutralCulture](./get_isneutralculture/)() const | ตรวจสอบว่าวัฒนธรรมเป็นกลางหรือไม่. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | ตรวจสอบวัตถุวัฒนธรรมเป็นแบบอ่านอย่างเดียวหรือไม่. |
| virtual int [get_KeyboardLayoutId](./get_keyboardlayoutid/)() const | ดึงตัวระบุ locale อินพุตที่ใช้งานอยู่. |
| virtual int [get_LCID](./get_lcid/)() const | ดึงตัวระบวัฒนธรรม. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() const | ดึงชื่อวัฒนธรรม. |
| virtual [String](../../system/string/) [get_NativeName](./get_nativename/)() const | ดึงชื่อท้องถิ่นของวัฒนธรรม. |
| virtual [NumberFormatInfoPtr](../numberformatinfoptr/) [get_NumberFormat](./get_numberformat/)() const | ดึงข้อมูลรูปแบบตัวเลข. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[CalendarPtr](../calendarptr/)\> [get_OptionalCalendars](./get_optionalcalendars/)() const | รายการปฏิทินที่สามารถใช้กับวัฒนธรรมนี้ได้. |
| virtual [CultureInfoPtr](../cultureinfoptr/) [get_Parent](./get_parent/)() const | ดึงวัฒนธรรมแม่. |
| virtual [TextInfoPtr](../textinfoptr/) [get_TextInfo](./get_textinfo/)() const | ดึงพารามิเตอร์ข้อความที่วัฒนธรรมใช้. |
| virtual [String](../../system/string/) [get_ThreeLetterISOLanguageName](./get_threeletterisolanguagename/)() const | ดึงรหัสภาษา ISO 639-2 ที่มีสามอักษร. |
| virtual [String](../../system/string/) [get_ThreeLetterWindowsLanguageName](./get_threeletterwindowslanguagename/)() const | ดึงรหัสสามอักษรสำหรับภาษาตามที่กำหนดใน API [Windows](../../system.windows/). |
| virtual [String](../../system/string/) [get_TwoLetterISOLanguageName](./get_twoletterisolanguagename/)() const | ดึงชื่อภาษา ISO สองอักษรที่สัมพันธ์กับวัฒนธรรม. |
| **bool** [get_UseUserOverride](./get_useuseroverride/)() const | ดึงแฟล็กที่บ่งชี้ว่า [CultureInfo](./) ใช้การตั้งค่าวัฒนธรรมที่ผู้ใช้เลือกหรือไม่. |
| [CultureInfoPtr](../cultureinfoptr/) [GetConsoleFallbackUICulture](./getconsolefallbackuiculture/)() const | ดึงวัฒนธรรมสำรองที่เหมาะสำหรับแอปพลิเคชันคอนโซล. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&) | ดึงวัฒนธรรมตามชื่อของมัน เหมือนกับ CreateSpecificCulture. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ดึงวัฒนธรรมตามชื่อของมัน. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfo](./getcultureinfo/)(**int32_t**) | ดึงวัฒนธรรมตามรหัส. |
| static [CultureInfoPtr](../cultureinfoptr/) [GetCultureInfoByIetfLanguageTag](./getcultureinfobyietflanguagetag/)(const [String](../../system/string/)\&) | เลิกใช้. ดึงอ็อบเจ็กต์ [CultureInfo](./) แบบอ่านอย่างเดียวโดยแท็กภาษาที่ระบุ RFC 4646. |
| static [ArrayPtr](../../system/arrayptr/)\<[CultureInfoPtr](../cultureinfoptr/)\> [GetCultures](./getcultures/)([CultureTypes](../culturetypes/)) | ดึงวัฒนธรรมที่อยู่ในประเภทที่ระบุ. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | ดึงอ็อบเจ็กต์รูปแบบสำหรับประเภทที่ระบุ. |
| int [GetHashCode](./gethashcode/)() const override | คืนค่ารหัสแฮชของอ็อบเจ็กต์. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์ ตรงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType ตรงกับตัวดำเนินการ 'is' ของ C#. |
| **bool** [IsInherited](./isinherited/)() const | ดึงแฟล็ก is-inherited สำหรับการใช้ภายในเท่านั้น. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาย่อยคลาสได้. |
| [CultureInfo](./)\& [operator=](./operator_equal/)(const [CultureInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาย่อยคลาสได้. |
| **bool** [operator==](./operator_equal_equal/)(const [CultureInfo](./)\&) const | เปรียบเทียบพารามิเตอร์วัฒนธรรม. |
| static [CultureInfoPtr](../cultureinfoptr/) [ReadOnly](./readonly/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | ดึงเวอร์ชันอ่านอย่างเดียวของวัฒนธรรม. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่กำหนด. |
| static void [set_CurrentCulture](./set_currentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | ตั้งค่าวัฒนธรรมสำหรับเธรดปัจจุบัน. |
| static void [set_CurrentUICulture](./set_currentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | ตั้งค่าวัฒนธรรม UI ของเธรดปัจจุบัน. |
| virtual void [set_DateTimeFormat](./set_datetimeformat/)([DateTimeFormatInfoPtr](../datetimeformatinfoptr/)) | ตั้งค่าข้อมูลรูปแบบวันที่. |
| static void [set_DefaultThreadCurrentCulture](./set_defaultthreadcurrentculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | ตั้งค่าวัฒนธรรมค่าเริ่มต้นในโดเมนแอปพลิเคชันปัจจุบัน. |
| static void [set_DefaultThreadCurrentUICulture](./set_defaultthreadcurrentuiculture/)(const [CultureInfoPtr](../cultureinfoptr/)\&) | ตั้งค่าวัฒนธรรม UI ค่าเริ่มต้นในโดเมนแอปพลิเคชันปัจจุบัน. |
| virtual void [set_NumberFormat](./set_numberformat/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | ดึงข้อมูลรูปแบบตัวเลข. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| [String](../../system/string/) [ToString](./tostring/)() const override | แปลงวัฒนธรรมเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกของคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้อ็อบเจ็กต์ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* คลาส [IFormatProvider](../../system/iformatprovider/)
* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Globalization](../)
* ไลบรารี [Aspose.Slides](../../)