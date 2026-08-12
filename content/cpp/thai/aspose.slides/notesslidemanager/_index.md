---
title: NotesSlideManager
second_title: Aspose.Slides สำหรับ API อ้างอิง C++
description: ผู้จัดการสไลด์โน้ต.
type: docs
weight: 4590
url: /th/aspose.slides/notesslidemanager/
---
## NotesSlideManager คลาส


ผู้จัดการสไลด์โน้ต.

```cpp
class NotesSlideManager : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Slide>>,
                          public Aspose::Slides::INotesSlideManager
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlide](../inotesslide/)\> [AddNotesSlide](./addnotesslide/)() override | ส่งคืนสไลด์โน้ตสำหรับสไลด์ปัจจุบัน หากไม่มีจะสร้างขึ้น |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลบทศนิยมสไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลบทศนิยมสไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlide](../inotesslide/)\> [get_NotesSlide](./get_notesslide/)() override | ส่งคืนสไลด์โน้ตสำหรับสไลด์ปัจจุบัน หากสไลด์ไม่มีสไลด์โน้ตจะคืนค่า null. อ่านอย่างเดียว [INotesSlide](../inotesslide/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อันตามวิธีการของ C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. อันตามการเรียกของ C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. อันตามออพเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | 구현 C# lock() 구문 잠금. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อันตามวิธีการของ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาในคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาในคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์แบบค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันตามค่าที่ระบุ |
| void [RemoveNotesSlide](./removenotesslide/)() override | ลบสไลด์โน้ตของสไลด์ปัจจุบัน |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็นพอยน์เตอร์แบบอ่อน (แทนที่จะเป็นแบบแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อันตามวิธีการของ C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 구현 C# typeof([System.Object](../../system/object/)) 구문 |
| void [Unlock](../../system/object/unlock/)() | 구현 C# lock() 구문 잠금 해제. 직접 호출하거나 [LockContext](../../system/lockcontext/) 감시 객체를 사용 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีเพิ่มโน้ตให้สไลด์ PowerPoint [Presentation](../presentation/) ที่ระบุ
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
auto presentation = System::MakeObject<Presentation>(dataDir + u"AccessSlides.pptx");

// เพิ่มโน้ตให้สไลด์แรก
System::SharedPtr<INotesSlideManager> mgr = presentation->get_Slides()->idx_get(0)->get_NotesSlideManager();
System::SharedPtr<INotesSlide> noteSlide = mgr->AddNotesSlide();
noteSlide->get_NotesTextFrame()->set_Text(u"Your Notes");

// บันทึกงานนำเสนอลงดิสก์
presentation->Save(u"RemoveNotesAtSpecificSlide_out.pptx", SaveFormat::Pptx);
```
 ตัวอย่างต่อไปนี้แสดงวิธีลบโน้ตออกจากสไลด์เฉพาะของ PowerPoint [Presentation](../presentation/)
```cpp
// สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนของไฟล์งานนำเสนอ
auto presentation = System::MakeObject<Presentation>(dataDir + u"AccessSlides.pptx");
// ลบโน้ตของสไลด์แรก
System::SharedPtr<INotesSlideManager> mgr = presentation->get_Slides()->idx_get(0)->get_NotesSlideManager();
mgr->RemoveNotesSlide();
// บันทึกงานนำเสนอลงดิสก์
presentation->Save(u"RemoveNotesAtSpecificSlide_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [DomObject](../domobject/)
* คลาส [INotesSlideManager](../inotesslidemanager/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)