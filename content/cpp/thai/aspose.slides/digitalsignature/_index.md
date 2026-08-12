---
title: DigitalSignature
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม.
type: docs
weight: 768
url: /th/aspose.slides/digitalsignature/
---
## DigitalSignature คลาส

ลายเซ็นดิจิทัลในไฟล์ที่ลงนาม.

```cpp
class DigitalSignature : public Aspose::Slides::IDigitalSignature
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [DigitalSignature](./digitalsignature/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\>) | สร้างวัตถุ [DigitalSignature](./) ใหม่ด้วยใบรับรองที่ระบุ |
|  [DigitalSignature](./digitalsignature/)([System::String](../../system/string/), [System::String](../../system/string/)) | สร้างวัตถุ [DigitalSignature](./) ใหม่ด้วยเส้นทางไฟล์ใบรับรองและรหัสผ่านที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/)\> [get_Certificate](./get_certificate/)() override | วัตถุใบรับรองที่ใช้ในการลงนามเอกสาร อ่านอย่างเดียว [X509Certificate2](../../system.security.cryptography.x509certificates/x509certificate2/) |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | วัตถุประสงค์ของลายเซ็น. อ่าน [System::String](../../system/string/) |
| **bool** [get_IsValid](./get_isvalid/)() override | หากลายเซ็นดิจิทัลนี้ถูกต้องและเอกสารไม่มีการดัดแปลงค่า จะเป็น true. อ่านอย่างเดียว **bool** |
| [System::DateTime](../../system/datetime/) [get_SignTime](./get_signtime/)() override | เวลาที่เอกสารถูกลงนาม. อ่านอย่างเดียว [System::DateTime](../../system/datetime/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชวัตถุแบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เทียบเคียงการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ targetType อธิบายหรือไม่. เทียบเคียงตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก. จริงๆแล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า. จริงๆแล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงกับวัตถุประเภทค่าโดยใช้ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | วัตถุประสงค์ของลายเซ็น. เขียน [System::String](../../system/string/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุแบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มลายเซ็นดิจิทัลจากใบรับรอง PFX ใน PowerPoint [Presentation](../presentation/). 
```cpp
// เริ่มต้นอินสแตนซ์ Presentation
auto pres = System::MakeObject<Presentation>();

// สร้างอ็อบเจ็กต์ DigitalSignature ด้วยไฟล์ PFX และรหัสผ่าน PFX
System::SharedPtr<DigitalSignature> signature = System::MakeObject<DigitalSignature>(u"testsignature1.pfx", u"testpass1");
// แสดงความคิดเห็นลายเซ็นดิจิทัลใหม่
signature->set_Comments(u"Aspose.Slides digital signing test.");
// เพิ่มลายเซ็นดิจิทัลลงในงานนำเสนอ
pres->get_DigitalSignatures()->Add(signature);
// บันทึกงานนำเสนอ
pres->Save(u"SomePresentationSigned.pptx", SaveFormat::Pptx);
```
ตัวอย่างโค้ดต่อไปนี้แสดงวิธีตรวจสอบความถูกต้องของลายเซ็นดิจิทัลของ PowerPoint [Presentation](../presentation/). 
```cpp
// เริ่มต้นอินสแตนซ์ Presentation
auto pres = System::MakeObject<Presentation>(u"SomePresentationSigned.pptx");

if (pres->get_DigitalSignatures()->get_Count() > 0)
{
    bool allSignaturesAreValid = true;
    System::Console::WriteLine(u"Signatures used to sign the presentation: ");
    // ตรวจสอบว่าลายเซ็นดิจิทัลทั้งหมดเป็นค่าถูกต้องหรือไม่
    for (auto&& signature : System::IterateOver(pres->get_DigitalSignatures()))
    {
        System::Console::WriteLine(signature->get_Certificate()->get_SubjectName()->get_Name() + u", " +
                                   signature->get_SignTime().ToString(u"yyyy-MM-dd HH:mm") + u" -- " +
                                   (signature->get_IsValid() ? System::String(u"VALID") : System::String(u"INVALID")));
        allSignaturesAreValid &= signature->get_IsValid();
    }

    if (allSignaturesAreValid)
    {
        System::Console::WriteLine(u"Presentation is genuine, all signatures are valid.");
    }
    else
    {
        System::Console::WriteLine(u"Presentation has been modified since signing.");
    }
}
```

## ดูเพิ่มเติม

* คลาส [IDigitalSignature](../idigitalsignature/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)