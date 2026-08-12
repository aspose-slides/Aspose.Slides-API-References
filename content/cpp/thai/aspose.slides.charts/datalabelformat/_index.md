---
title: DataLabelFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงตัวเลือกการจัดรูปแบบสำหรับ DataLabel.
type: docs
weight: 391
url: /th/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat คลาส


แสดงตัวเลือกการจัดรูปแบบสำหรับ [DataLabel](../datalabel/).

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | เปรียบเทียบกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C#-style โดยที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C#-style โดยที่ NaN สองค่าถูกพิจารณาเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | คืนค่าแผนภูมิ. อ่านอย่างเดียว [IChart](../ichart/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | แสดงรูปแบบของป้ายข้อมูล. อ่านอย่างเดียว [IFormat](../iformat/) |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | อ่าน **bool** |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. อ่าน [System::String](../../system/string/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../../aspose.slides/idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | คืนค่า parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | แสดงตำแหน่งของป้ายข้อมูล. อ่าน [LegendDataLabelPosition](../legenddatalabelposition/) |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | ตั้งหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. อ่าน [System::String](../../system/string/) |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงค่าขนาดฟอง. False ซ่อน. อ่าน **bool** |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิกำหนด. True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลบนแผนภูมิ. False ซ่อน. อ่าน **bool** |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | กำหนดว่าป้ายข้อมูลของแผนภูมิกำหนดจะแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | แสดงพฤติกรรมการแสดงค่าของเซลล์ในป้ายข้อมูลของแผนภูมิกำหนด. True แสดงค่าของเซลล์. False ซ่อน. อ่าน **bool** |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงเส้นนำ. False ซ่อน. อ่าน **bool** |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | แสดงพฤติกรรมการแสดงคีย์ของตารางอธิบายป้ายข้อมูลในแผนภูมิกำหนด. True หากคีย์ของตารางอธิบายป้ายข้อมูลมองเห็นได้. อ่าน **bool** |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงค่าร้อยละ. False ซ่อน. อ่าน **bool** |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | คืนค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. True เพื่อแสดงชื่อซีรีส์. False ซ่อน. อ่าน **bool** |
| **bool** [get_ShowValue](./get_showvalue/)() override | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงค่าร้อยละ. False ซ่อน. อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | คืนฟอร์แมตข้อความของแผนภูมิ. อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | คืนค่าแฮชโค้ด |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเท่าการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType. เทียบเท่าตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่าวิธี [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการทำสำเนาชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างคัดลอกซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างคัดลอกซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ค่าประเภทอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการนับอ้างอิงร่วมตามค่าที่ระบุ |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | เขียน **bool** |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | แสดงสตริงรูปแบบสำหรับวัตถุ DataLabels. เขียน [System::String](../../system/string/) |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | แสดงตำแหน่งของป้ายข้อมูล. เขียน [LegendDataLabelPosition](../legenddatalabelposition/) |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | ตั้งหรือคืนค่า Variant ที่แสดงตัวคั่นที่ใช้สำหรับป้ายข้อมูลบนแผนภูมิ. เขียน [System::String](../../system/string/) |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | แสดงพฤติกรรมการแสดงค่าขนาดฟองของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงค่าขนาดฟอง. False ซ่อน. เขียน **bool** |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | แสดงพฤติกรรมการแสดงชื่อหมวดหมู่ของป้ายข้อมูลในแผนภูมิกำหนด. True เพื่อแสดงชื่อหมวดหมู่สำหรับป้ายข้อมูลบนแผนภูมิ. False ซ่อน. เขียน **bool** |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | กำหนดว่าป้ายข้อมูลของแผนภูมิกำหนดจะแสดงเป็นการอธิบายข้อมูลหรือเป็นป้ายข้อมูล |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | แสดงพฤติกรรมการแสดงค่าของเซลล์ในป้ายข้อมูลของแผนภูมิกำหนด. True แสดงค่าของเซลล์. False ซ่อน. เขียน **bool** |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | แสดงพฤติกรรมการแสดงเส้นนำของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงเส้นนำ. False ซ่อน. เขียน **bool** |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | แสดงพฤติกรรมการแสดงคีย์ของตารางอธิบายป้ายข้อมูลในแผนภูมิกำหนด. True หากคีย์ของตารางอธิบายป้ายข้อมูลมองเห็นได้. เขียน **bool** |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงค่าร้อยละ. False ซ่อน. เขียน **bool** |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | ตั้งค่า Boolean เพื่อระบุพฤติกรรมการแสดงชื่อซีรีส์สำหรับป้ายข้อมูลบนแผนภูมิ. True เพื่อแสดงชื่อซีรีส์. False ซ่อน. เขียน **bool** |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | แสดงพฤติกรรมการแสดงค่าร้อยละของป้ายข้อมูลในแผนภูมิกำหนด. True แสดงค่าร้อยละ. False ซ่อน. เขียน **bool** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่าวิธี [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดให้แปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [PVIObject](../../aspose.slides/pviobject/)
* คลาส [IDataLabelFormat](../idatalabelformat/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)