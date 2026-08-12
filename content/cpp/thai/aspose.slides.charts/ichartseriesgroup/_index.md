---
title: IChartSeriesGroup
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงกลุ่มของชุดข้อมูล.
type: docs
weight: 846
url: /th/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup คลาส


Represents group of series.

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าเทียบกันเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่ NaN สองค่าเทียบกันเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | ระบุวิธีการแสดงค่าขนาดฟองอากาศบนแผนภูมิบับเบิล. อ่าน [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น) อ่าน **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | ส่งคืนแผนภูมิ. อ่านอย่างเดียว [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | ส่งคืนชุดข้อมูลแผนภูมิในกลุ่มที่ตำแหน่งที่ระบุ. |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต) อ่าน **uint8_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | รับมุมของชิ้นแรกของแผนภูมิวงปัดหรือโดนัท, เป็นองศา (จากบนโดยเข็มนาฬิกา, ตั้งแต่ 0 ถึง 360 องศา) อ่าน **uint16_t**. |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | ส่งคืนระยะห่างในรูปเปอร์เซ็นต์ของความกว้างของเครื่องหมาย ระหว่างชุดข้อมูลในแผนภูมิ 3 มิติ. อ่าน **uint16_t**. |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. อ่าน **uint16_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | จริงหากแผนภูมิมีเส้นชุดข้อมูล. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | ระบุรูปแบบ HiLowLines. HiLowLines ถูกใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในชุดข้อมูลมีสีที่ต่างกัน. อ่าน **bool**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | ระบุว่าบาร์และคอลัมน์ควรทับกันเท่าไหร่บนแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายที่สองหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. ส่งคืนจุดข้อมูลที่ควรวาดในพายที่สองหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie ตามดัชนี. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายที่สองหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | ระบุค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ในพายที่สองหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | บ่งบอกว่าชุดข้อมูลของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | ระบุขนาดของพายที่สองหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | ส่งคืนคอลเลกชันแบบอ่านอย่างเดียวของชุดข้อมูลแผนภูมิ. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | ส่งคืนประเภทของกลุ่มชุดข้อมูลนี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | ให้การเข้าถึงบาร์ขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดให้ทำแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เหมือนกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เหมือนกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดให้ทำการคลoning ของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | ระบุวิธีการแสดงค่าขนาดฟองอากาศบนแผนภูมิบับเบิล. เขียน [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น) เขียน **int32_t**. |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | ระบุขนาดของรูในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต) เขียน **uint8_t**. |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | ตั้งมุมของชิ้นแรกของแผนภูมิพายหรือโดนัทเป็นองศา (จากบนโดยเข็มนาฬิกา, ตั้งแต่ 0 ถึง 360 องศา) เขียน **uint16_t**. |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | ตั้งระยะห่างเป็นเปอร์เซ็นต์ของความกว้างของเครื่องหมาย ระหว่างชุดข้อมูลในแผนภูมิ 3 มิติ. เขียน **uint16_t**. |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | ตั้งช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. เขียน **uint16_t**. |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | จริงหากแผนภูมิมีเส้นชุดข้อมูล. ใช้กับแผนภูมิ stacked bar และ OfPie. เขียน **bool**. |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในชุดข้อมูลมีสีที่ต่างกัน. เขียน **bool**. |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | ระบุว่าบาร์และคอลัมน์ควรทับกันเท่าไหร่บนแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายที่สองหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. เขียน [PieSplitType](../piesplittype/). |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | ระบุค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ในพายที่สองหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. เขียน **double**. |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | ระบุขนาดของพายที่สองหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). เขียน **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่ใช้ร่วมกัน. ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันและคืนค่า. ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดให้แปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวน weak reference. ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference. ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับ ChartSeriesGroupCollection คลาสและ CombinableSeriesTypesGroup enum. 2) กลุ่มของชุดข้อมูลมีคุณสมบัติของชุดข้อมูลบางอย่างที่เป็นค่าที่เหมือนกันสำหรับแต่ละชุดข้อมูลในกลุ่ม ("series group properties"). "Series group properties" ใน [ChartSeriesGroup](../chartseriesgroup/) คลาส เป็น อ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวใน [ChartSeries](../chartseries/) คลาส. 

## ดูเพิ่มเติม

* คลาส [IChartComponent](../ichartcomponent/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)