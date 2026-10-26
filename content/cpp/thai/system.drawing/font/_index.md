---
title: Font
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "แสดงถึงรูปแบบเฉพาะสำหรับข้อความ รวมถึงแบบอักษร, ขนาด, และสไตล์ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด ควรห่อคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 79
url: /th/system.drawing/font/
---
## คลาส Font


แสดงถึงรูปแบบเฉพาะสำหรับข้อความ รวมถึงฟอนต์, ขนาด, และสไตล์ อ็อบเจ็กต์ของคลาสนี้ควรถูกจัดสรรโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบข้อผิดพลาด (assertion) เสมอห่อคลาสนี้เข้าในพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class Font : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | คืนสำเนาของฟอนต์ปัจจุบัน |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรระบบปฏิบัติการทั้งหมดที่ออบเจ็กต์ปัจจุบันได้ครอบครอง |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ตรวจสอบว่าออบเจ็กต์ปัจจุบันและออบเจ็กต์ที่ระบุเป็นอันเดียวกันหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | สร้างอินสแตนซ์ใหม่ของคลาส [Font](./) ที่แสดงถึงฟอนต์ที่มีอยู่ตามที่ระบุพร้อมสไตล์ฟอนต์ที่ระบุ |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | สร้างอินสแตนซ์ใหม่ของคลาส [Font](./) |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | สร้างอินสแตนซ์ใหม่ของคลาส [Font](./) |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | สร้างอินสแตนซ์ใหม่ของคลาส [Font](./) |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | สร้างอินสแตนซ์ใหม่ของคลาส [Font](./) |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | ยังไม่ได้ดำเนินการ |
| **bool** [get_Bold](./get_bold/)() | ตรวจสอบว่าฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงมีสไตล์หนา (bold) หรือไม่ |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | คืนชื่อฟอนต์ของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | คืนสไตล์ของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | คืนค่าที่ระบุชุดอักขระ GDI ที่ฟอนต์ของออบเจ็กต์ปัจจุบันใช้ |
| int [get_Height](./get_height/)() | คืนระยะห่างบรรทัดของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงหน่วยเป็นพิกเซล |
| **bool** [get_Italic](./get_italic/)() | ตรวจสอบว่าฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงมีสไตล์เอียง (italic) หรือไม่ |
| [String](../../system/string/) [get_Name](./get_name/)() | คืนชื่อฟอนต์ของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | คืนชื่อฟอนต์ที่ระบุเดิม |
| **float** [get_Size](./get_size/)() | คืนขนาด em ของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง วัดเป็นหน่วยที่กำหนดโดยคุณสมบัติ Unit |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | คืนขนาด em ของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงเป็นจุด |
| **bool** [get_Strikeout](./get_strikeout/)() | ตรวจสอบว่าฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงมีสไตล์ขีดฆ่า (strikeout) หรือไม่ |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | คืนสไตล์ของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง |
| **bool** [get_Underline](./get_underline/)() | ตรวจสอบว่าฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงมีสไตล์ขีดเส้นใต้ (underline) หรือไม่ |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | คืนหน่วยการวัดสำหรับฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์แบบกำหนดเองได้ |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | คืนระยะห่างบรรทัดของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดง ในหน่วยปัจจุบันของออบเจ็กต์ [Graphics](../graphics/) ที่ระบุ |
| **float** [GetHeight](./getheight/)(**float**) | คืนความสูงของฟอนต์ที่ออบเจ็กต์ปัจจุบันแสดงเมื่อวาดบนอุปกรณ์แสดงผลโดยมีความละเอียดแนวตั้งที่ระบุ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเคียงกับออเปอร์เรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ชนิดค่ากับ nullptr ด้วยการอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่ใช้ร่วมกันตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้เปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Drawing](../)
* ไลบรารี [Aspose.Slides](../../)