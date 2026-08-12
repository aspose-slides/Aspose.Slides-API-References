---
title: IDataLabelFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
type: docs
weight: 963
url: /th/aspose.slides.charts/idatalabelformat/
---
## IDataLabelFormat คลาส

แสดงตัวเลือกการจัดรูปแบบสำหรับ [DataLabel](../datalabel/).

```cpp
class IDataLabelFormat : public Aspose::Slides::Charts::IFormattedTextContainer
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# โดยที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# โดยที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | คืนค่าแผนภูมิ. อ่านอย่างเดียว [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | แสดงรูปแบบของป้ายข้อมูล. อ่านอย่างเดียว [IFormat](../iformat/). |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | อ่าน **bool**. |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน [System::String](../../system/string/). |
| virtual [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() | แสดงตำแหน่งของป้ายข้อมูล. อ่าน [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนค่าสไลด์การนำเสนอ. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [System::String](../../system/string/) [get_Separator](./get_separator/)() | ตั้งค่าหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน [System::String](../../system/string/). |
| virtual **bool** [get_ShowBubbleSize](./get_showbubblesize/)() | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าขนาดฟอง. False ซ่อน. อ่าน **bool**. |
| virtual **bool** [get_ShowCategoryName](./get_showcategoryname/)() | แสดงพฤติกรรมการแสดงชื่อหมวดของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงชื่อหมวดสำหรับป้ายข้อมูลบนแผนภูมิ. False ซ่อน. อ่าน **bool**. |
| virtual **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการเรียกข้อมูลหรือเป็นป้ายข้อมูล. |
| virtual **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() | แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าเซลล์. False ซ่อน. อ่าน **bool**. |
| virtual **bool** [get_ShowLeaderLines](./get_showleaderlines/)() | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงเส้นนำ. False ซ่อน. อ่าน **bool**. |
| virtual **bool** [get_ShowLegendKey](./get_showlegendkey/)() | แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ. True หากคีย์คำอธิบายของป้ายข้อมูลมองเห็นได้. อ่าน **bool**. |
| virtual **bool** [get_ShowPercentage](./get_showpercentage/)() | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False ซ่อน. อ่าน **bool**. |
| virtual **bool** [get_ShowSeriesName](./get_showseriesname/)() | คืนค่า Boolean เพื่อบ่งชี้พฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. True แสดงชื่อซีรีส์. False ซ่อน. อ่าน **bool**. |
| virtual **bool** [get_ShowValue](./get_showvalue/)() | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False ซ่อน. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนค่าฐานสไลด์. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | คืนค่ารูปแบบข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นรูปแบบของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยให้ทำแฮชของวัตถุที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นรูปแบบของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นรูปแบบของตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | นำการล็อก() ของ C# ไปใช้. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นรูปแบบของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยให้ทำสำเนาชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาในคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบโดยอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การชี้เฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การชี้เฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | เขียน **bool**. |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. เขียน [System::String](../../system/string/). |
| virtual void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) | แสดงตำแหน่งของป้ายข้อมูล. เขียน [LegendDataLabelPosition](../legenddatalabelposition/). |
| virtual void [set_Separator](./set_separator/)([System::String](../../system/string/)) | ตั้งค่าหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. เขียน [System::String](../../system/string/). |
| virtual void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าขนาดฟอง. False ซ่อน. เขียน **bool**. |
| virtual void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) | แสดงพฤติกรรมการแสดงชื่อหมวดของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงชื่อหมวดสำหรับป้ายข้อมูลบนแผนภูมิ. False ซ่อน. เขียน **bool**. |
| virtual void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) | กำหนดว่าป้ายข้อมูลของแผนภูมิที่ระบุจะถูกแสดงเป็นการเรียกข้อมูลหรือเป็นป้ายข้อมูล. |
| virtual void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) | แสดงพฤติกรรมการแสดงค่าเซลล์ของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าเซลล์. False ซ่อน. เขียน **bool**. |
| virtual void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงเส้นนำ. False ซ่อน. เขียน **bool**. |
| virtual void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) | แสดงพฤติกรรมการแสดงคีย์คำอธิบายของป้ายข้อมูลในแผนภูมิที่ระบุ. True หากคีย์คำอธิบายของป้ายข้อมูลมองเห็นได้. เขียน **bool**. |
| virtual void [set_ShowPercentage](./set_showpercentage/)(**bool**) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False ซ่อน. เขียน **bool**. |
| virtual void [set_ShowSeriesName](./set_showseriesname/)(**bool**) | ตั้งค่า Boolean เพื่อบ่งชี้พฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. True แสดงชื่อซีรีส์. False ซ่อน. เขียน **bool**. |
| virtual void [set_ShowValue](./set_showvalue/)(**bool**) | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิที่ระบุ. True แสดงค่าร้อยละ. False ซ่อน. เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนการใช้ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นรูปแบบของเมธอด C# [Object.ToString()](../../system/object/tostring/). ช่วยให้แปลงวัตถุที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | นำโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# ไปใช้. |
| void [Unlock](../../system/object/unlock/)() | ปลดล็อก() ของ C# ไปใช้. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IFormattedTextContainer](../iformattedtextcontainer/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)