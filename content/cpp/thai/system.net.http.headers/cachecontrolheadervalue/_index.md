---
title: CacheControlHeaderValue
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: "เป็นตัวแทนของค่าในส่วนหัว 'Cache-Control' คอนเทนท์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ เสมอห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 14
url: /th/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue คลาส


เป็นตัวแทนของค่าในส่วนหัว 'Cache-Control' คอนเทนต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ เฉพาะควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | สร้างอินสแตนซ์ใหม่ |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | คืนค่าคอลเลกชันของโทเคน cache-extension |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | รับค่ามากสุดของอายุเป็นวินาทีที่กำหนดช่วงเวลาที่ไคลเอนต์จะยอมรับการตอบสนอง |
| **bool** [get_MaxStale](./get_maxstale/)() | รับค่าที่กำหนดว่าไคลเอนต์จะยอมรับการตอบสนองที่หมดอายุหรือไม่ |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | รับค่าที่เป็นวินาทีซึ่งกำหนดช่วงเวลาที่ไคลเอนต์จะยอมรับการตอบสนองที่หมดอายุ |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | รับค่าที่กำหนดอายุความสดของข้อมูล |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | รับค่าที่กำหนดว่าเซิร์ฟเวอร์ต้องการการตรวจสอบใหม่ของรายการแคชเมื่อมันล้าสมัยหรือไม่ |
| **bool** [get_NoCache](./get_nocache/)() | รับค่าที่กำหนดว่าไคลเอนต์จะยอมรับการตอบสนองที่แคชไว้หรือไม่ |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | รับคอลเลกชันของชื่อฟิลด์ใน directive 'no-cache' ของส่วนหัว 'Cache-Control' |
| **bool** [get_NoStore](./get_nostore/)() | รับค่าที่กำหนดว่าแคชต้องไม่เก็บส่วนใดของคำขอหรือการตอบสนอง HTTP |
| **bool** [get_NoTransform](./get_notransform/)() | รับค่าที่กำหนดว่าแคชหรือพร็อกซีต้องไม่เปลี่ยนส่วนใดของเนื้อหาเอนทิตี้ |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | รับค่าที่กำหนดว่าไคลเอนต์ต้องใช้เฉพาะรายการที่แคชไว้เท่านั้น |
| **bool** [get_Private](./get_private/)() | รับค่าที่กำหนดว่าข้อความหรือส่วนของการตอบสนอง HTTP นั้นตั้งใจสำหรับผู้ใช้คนเดียวและต้องไม่ถูกแคชโดยแคชร่วม |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | รับคอลเลกชันของชื่อฟิลด์ใน directive 'private' ของส่วนหัว 'Cache-Control' |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | รับค่าที่กำหนดว่าเซิร์ฟเวอร์ต้องการการตรวจสอบใหม่ของรายการแคชเมื่อมันล้าสมัยสำหรับแคชของ user agent ที่แชร์ |
| **bool** [get_Public](./get_public/)() | รับค่าที่กำหนดว่าการตอบสนอง HTTP สามารถถูกแคชโดยแคชใดๆ ได้หรือไม่ |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | รับค่าสำหรับอายุสูงสุดที่แชร์เป็นวินาทีซึ่งจะทับค่า directive 'max-age' ในส่วนหัว 'Cache-Control' หรือส่วนหัว 'Expires' สำหรับแคชที่แชร์ |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | แปลงสตริงที่ส่งเข้ามาจากตำแหน่งที่ระบุเป็นอินสแตนซ์ของคลาส [CacheControlHeaderValue](./) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และอนุญาตให้สร้างสำเนาในซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และอนุญาตให้สร้างสำเนาในซับคลาส |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | แปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [CacheControlHeaderValue](./) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบโดยอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงด้วยค่าที่ระบุ |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | ตั้งค่ามากสุดของอายุเป็นวินาทีที่กำหนดช่วงเวลาที่ไคลเอนต์จะยอมรับการตอบสนอง |
| void [set_MaxStale](./set_maxstale/)(**bool**) | ตั้งค่าที่กำหนดว่าไคลเอนต์จะยอมรับการตอบสนองที่หมดอายุหรือไม่ |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | ตั้งค่าที่เป็นวินาทีซึ่งกำหนดช่วงเวลาที่ไคลเอนต์จะยอมรับการตอบสนองที่หมดอายุ |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | ตั้งค่าที่กำหนดอายุความสดของข้อมูล |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | ตั้งค่าที่กำหนดว่าเซิร์ฟเวอร์ต้องการการตรวจสอบใหม่ของรายการแคชเมื่อมันล้าสมัยหรือไม่ |
| void [set_NoCache](./set_nocache/)(**bool**) | ตั้งค่าที่กำหนดว่าไคลเอนต์จะยอมรับการตอบสนองที่แคชไว้หรือไม่ |
| void [set_NoStore](./set_nostore/)(**bool**) | ตั้งค่าที่กำหนดว่าแคชต้องไม่เก็บส่วนใดของคำขอหรือการตอบสนอง HTTP |
| void [set_NoTransform](./set_notransform/)(**bool**) | ตั้งค่าที่กำหนดว่าแคชหรือพร็อกซีต้องไม่เปลี่ยนส่วนใดของเนื้อหาเอนทิตี้ |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | ตั้งค่าที่กำหนดว่าไคลเอนต์ต้องใช้เฉพาะรายการที่แคชไว้เท่านั้น |
| void [set_Private](./set_private/)(**bool**) | ตั้งค่าที่กำหนดว่าข้อความหรือส่วนของการตอบสนอง HTTP นั้นตั้งใจสำหรับผู้ใช้คนเดียวและต้องไม่ถูกแคชโดยแคชร่วม |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | ตั้งค่าที่กำหนดว่าเซิร์ฟเวอร์ต้องการการตรวจสอบใหม่ของรายการแคชเมื่อมันล้าสมัยสำหรับแคชของ user agent ที่แชร์ |
| void [set_Public](./set_public/)(**bool**) | ตั้งค่าที่กำหนดว่าการตอบสนอง HTTP สามารถถูกแคชโดยแคชใดก็ได้หรือไม่ |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | ตั้งค่าสำหรับอายุสูงสุดที่แชร์เป็นวินาทีซึ่งจะทับค่า directive 'max-age' ในส่วนหัว 'Cache-Control' หรือส่วนหัว 'Expires' สำหรับแคชที่แชร์ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| [String](../../system/string/) [ToString](./tostring/)() const override | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | พยายามแปลงสตริงที่ส่งเข้ามาเป็นอินสแตนซ์ของคลาส [CacheControlHeaderValue](./) |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรักต์ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลอดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ICloneable](../../system/icloneable/)
* เนมสเปซ [System::Net::Http::Headers](../)
* ไลบรารี [Aspose.Slides](../../)