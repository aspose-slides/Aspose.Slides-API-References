---
title: TimeZoneInfo
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงข้อมูลที่อธิบายเขตเวลาหนึ่งเฉพาะ. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1340
url: /th/system/timezoneinfo/
---
## TimeZoneInfo คลาส

แสดงข้อมูลที่อธิบายเขตเวลาเฉพาะ ตัวอย่างของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดระหว่างทำงานและ/หรือการขัดจ้าง การอ้างอิงคลาสนี้ควรห่อหุ้มด้วยพอยเตอร์ [System::SmartPtr](../smartptr/) และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class TimeZoneInfo : public System::IEquatable<TimeZoneInfoPtr>
```

## เมธอด

| Method | Description |
| --- | --- |
| static void [ClearCachedData](./clearcacheddata/)() | ล้างข้อมูลเขตเวลาที่แคชไว้ |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) เวลาจากเขตเวลาหนึ่งไปยังอีกเขตเวลา |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTime](./converttime/)(const [DateTimeOffset](../datetimeoffset/)\&, const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) เวลาให้เป็นเวลาในเขตเวลาที่ระบุ |
| static [DateTime](../datetime/) [ConvertTime](./converttime/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | [Convert](../convert/) เวลาให้เป็นเวลาในเขตเวลาที่ระบุ |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&) | [Convert](../convert/) เวลาให้เป็นเวลาในเขตเวลาที่ระบุ |
| static [DateTimeOffset](../datetimeoffset/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)(const [DateTimeOffset](../datetimeoffset/)\&, const [String](../string/)\&) | [Convert](../convert/) เวลาให้เป็นเวลาในเขตเวลาที่ระบุ |
| static [DateTime](../datetime/) [ConvertTimeBySystemTimeZoneId](./converttimebysystemtimezoneid/)([DateTime](../datetime/), const [String](../string/)\&, const [String](../string/)\&) | [Convert](../convert/) เวลาให้เป็นเวลาในเขตเวลาที่ระบุ |
| static [DateTime](../datetime/) [ConvertTimeFromUtc](./converttimefromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | แปลงเวลา UTC ให้เป็นเวลาในเขตเวลาที่ระบุ |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | แปลงเวลาให้เป็นเวลา UTC |
| static [DateTime](../datetime/) [ConvertTimeToUtc](./converttimetoutc/)([DateTime](../datetime/)) | แปลงเวลาให้เป็นเวลา UTC |
| static [DateTime](../datetime/) [ConvertTimeToUtcNoThrow](./converttimetoutcnothrow/)([DateTime](../datetime/)) | แปลงเวลาให้เป็นเวลา UTC สำหรับการใช้งานภายใน |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&, **bool**) | สร้างเขตเวลาแบบกำหนดเอง |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&, const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\>\&) | สร้างเขตเวลาแบบกำหนดเอง |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [CreateCustomTimeZone](./createcustomtimezone/)(const [String](../string/)\&, [TimeSpan](../timespan/), const [String](../string/)\&, const [String](../string/)\&) | สร้างเขตเวลาแบบกำหนดเอง |
| **bool** [Equals](./equals/)([SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([TimeZoneInfoPtr](../timezoneinfoptr/)) override | กำหนดว่าวัตถุปัจจุบันและวัตถุที่ระบุเท่ากันหรือไม่ |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [FindSystemTimeZoneById](./findsystemtimezonebyid/)(const [String](../string/)\&) | รับเขตเวลาที่มีตัวระบุที่ระบุ |
| [TimeSpan](../timespan/) [get_BaseUtcOffset](./get_baseutcoffset/)() const | คืนค่าอินสแตนซ์ของ [TimeSpan](../timespan/) ที่แสดงช่วงเวลาระหว่างเวลา มาตรฐานของเขตเวลาปัจจุบันและเวลา UTC |
| [String](../string/) [get_DaylightName](./get_daylightname/)() const | รับชื่อสำหรับเวลาออมแสงของเขตเวลาปัจจุบัน |
| [String](../string/) [get_DisplayName](./get_displayname/)() const | รับชื่อของเขตเวลาปัจจุบัน |
| [String](../string/) [get_Id](./get_id/)() const | คืนค่าตัวระบุของเขตเวลาที่ออบเจ็กต์ปัจจุบันแสดง |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Local](./get_local/)() | คืนค่าอินสแตนซ์ของ [TimeZoneInfo](./) ที่เป็นเขตเวลาแบบท้องถิ่น |
| [String](../string/) [get_StandardName](./get_standardname/)() const | รับชื่อสำหรับเวลาแบบมาตรฐานของเขตเวลาปัจจุบัน |
| **bool** [get_SupportsDaylightSavingTime](./get_supportsdaylightsavingtime/)() const | รับค่าสถานะที่บ่งชี้ว่าเขตเวลามีกฎเวลาออมแสงหรือไม่ |
| static [TimeZoneInfoPtr](../timezoneinfoptr/) [get_Utc](./get_utc/)() | คืนค่าอินสแตนซ์ของ [TimeZoneInfo](./) ที่เป็นเขตเวลา UTC |
| [ArrayPtr](../arrayptr/)\<[AdjustmentRulePtr](./adjustmentruleptr/)\> [GetAdjustmentRules](./getadjustmentrules/)() const | คืนค่าอาร์เรย์ที่ประกอบด้วยวัตถุ **AdjustmentRule** ที่แสดงกฎการปรับที่ใช้กับวัตถุ [TimeZoneInfo](./) ปัจจุบัน |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)([DateTime](../datetime/)) const | รับวันที่และเวลาผิด UTC ที่วันและเวลาที่ระบุสามารถแมปได้ |
| [ArrayPtr](../arrayptr/)\<[TimeSpan](../timespan/)\> [GetAmbiguousTimeOffsets](./getambiguoustimeoffsets/)(const [DateTimeOffset](../datetimeoffset/)\&) const | รับวันที่และเวลาผิด UTC ที่วันและเวลาที่ระบุสามารถแมปได้ |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| int [GetHashCode](./gethashcode/)() const override | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถแฮชวัตถุที่กำหนดเองได้ |
| static [SharedPtr](../sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<[TimeZoneInfoPtr](../timezoneinfoptr/)\>\> [GetSystemTimeZones](./getsystemtimezones/)() | รับคอลเลกชันที่เรียงลำดับของเขตเวลาทั้งหมดที่มีในระบบท้องถิ่น |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)([DateTime](../datetime/)) const | คำนวณความแตกต่างระหว่างเวลาในเขตเวลานี้และเวลา UTC สำหรับวันและเวลาที่ระบุ |
| [TimeSpan](../timespan/) [GetUtcOffset](./getutcoffset/)(const [DateTimeOffset](../datetimeoffset/)\&) const | คำนวณความแตกต่างระหว่างเวลาในเขตเวลานี้และเวลา UTC สำหรับวันและเวลาที่ระบุ |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) | ฟังก์ชันช่วยเหลือภายในที่คืนค่าออฟเซ็ต UTC สำหรับวัน-เวลา UTC ในเขตเวลาที่ระบุ สำหรับการใช้งานภายใน |
| static [TimeSpan](../timespan/) [GetUtcOffsetFromUtc](./getutcoffsetfromutc/)([DateTime](../datetime/), const [TimeZoneInfoPtr](../timezoneinfoptr/)\&, **bool**\&, **bool**\&) | ฟังก์ชันช่วยเหลือภายในที่คืนค่าออฟเซ็ต UTC สำหรับวัน-เวลา UTC ในเขตเวลาที่ระบุ สำหรับการใช้งานภายใน |
| [TimeSpan](../timespan/) [GetUtcOffsetNoThrow](./getutcoffsetnothrow/)([DateTime](../datetime/)) const | คำนวณความแตกต่างระหว่างเวลาในเขตเวลานี้และเวลา UTC สำหรับวันและเวลาที่ระบุ สำหรับการใช้งานภายใน |
| **bool** [HasSameRules](./hassamerules/)(const [TimeZoneInfoPtr](../timezoneinfoptr/)\&) const | ตรวจสอบว่าเขตเวลาปัจจุบันและเขตเวลาอื่นมีกฎการปรับเดียวกันหรือไม่ |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ คล้ายกับออปเรเตอร์ C# `is` |
| **bool** [IsAmbiguousTime](./isambiguoustime/)([DateTime](../datetime/)) const | ตรวจสอบว่าวันและเวลาที่ระบุเป็นค่าที่คลุมเครือและสามารถแมปกับเวลา UTC หลายค่าได้หรือไม่ |
| **bool** [IsAmbiguousTime](./isambiguoustime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | ตรวจสอบว่าวันและเวลาที่ระบุเป็นค่าที่คลุมเครือและสามารถแมปกับเวลา UTC หลายค่าได้หรือไม่ |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)([DateTime](../datetime/)) const | ตรวจสอบว่าวันและเวลาที่ระบุอยู่ในช่วงเวลาออมแสงหรือไม่ |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)(const [DateTimeOffset](../datetimeoffset/)\&) const | ตรวจสอบว่าวันและเวลาที่ระบุอยู่ในช่วงเวลาออมแสงหรือไม่ |
| **bool** [IsDaylightSavingTimeNoThrow](./isdaylightsavingtimenothrow/)([DateTime](../datetime/)) const | ตรวจสอบว่าวันและเวลาที่ระบุอยู่ในช่วงเวลาออมแสงหรือไม่ |
| **bool** [IsInvalidTime](./isinvalidtime/)([DateTime](../datetime/)) const | ตรวจสอบว่าวันและเวลาเป็นค่าว่างหรือไม่ |
| void [Lock](../object/lock/)() | Implement คำสั่ง C# lock() เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนชนิดที่กำหนดเองได้ |
|  [Object](../object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกของคลาสย่อยทำงาน |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดให้คอนสตรัคเตอร์คัดลอกของคลาสย่อยทำงาน |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะแบ่งปัน) อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| [String](../string/) [ToString](./tostring/)() const override | คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static [DateTime](../datetime/) [TransitionTimeToDateTime](./transitiontimetodatetime/)(**int32_t**, const **TransitionTime**\&) | ฟังก์ชันช่วยที่แปลงปีและ **TransitionTime** ไปเป็น [DateTime](../datetime/) |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implement คำสั่ง C# typeof([System.Object](../object/)) |
| void [Unlock](../object/unlock/)() | Implement คำสั่ง C# lock() เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## การกำหนด typedef

| Typedef | Description |
| --- | --- |
| [AdjustmentRulePtr](./adjustmentruleptr/) | นามแฝงสำหรับพอยเตอร์ที่แชร์ไปยังอินสแตนซ์ของคลาส **AdjustmentRule** |

## ดูเพิ่มเติม

* คลาส [IEquatable](../iequatable/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)