---
title: ChartSeriesGroup
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: แสดงกลุ่มของ series.
type: docs
weight: 300
url: /th/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup คลาส


Represents group of series.

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ตรรกะ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบจุดลอยของ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น. |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิฟอง. อ่าน [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | ระบุค่าสเกลแฟกเตอร์สำหรับแผนภูมิฟอง (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | ส่งคืน series ของแผนภูมิในกลุ่มที่ตำแหน่งที่ระบุ. |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | ระบุขนาดของรูในแผนภูมิดอนัท (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน **uint8_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | รับค่าองศาของชิ้นแรกของพายหรือดอนัท (ตามเข็มนาฬิกาจากด้านบน, จาก 0 ถึง 360 องศา). อ่าน **uint16_t**. |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | ส่งคืนระยะทางเป็นเปอร์เซ็นต์ของความกว้างของมาร์กเกอร์ระหว่าง series ของข้อมูลในแผนภูมิ 3 มิติ. อ่าน **uint16_t**. |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. อ่าน **uint16_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | เป็นจริงหากแผนภูมิมีเส้น series. ใช้กับแผนภูมิแท่งซ้อนและ OfPie. อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | ระบุรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวใน series มีสีต่างกัน. อ่าน **bool**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | ระบุเปอร์เซ็นต์การทับซ้อนของแท่งและคอลัมน์บนแผนภูมิ 2 มิติ (จาก -100% ถึง 100%). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | ระบุวิธีการกำหนดว่า data point ใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | ข้อมูลการแยกส่วนแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนแบบกำหนดเอง. ส่งคืน data point ที่จะวาดในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie ตามตำแหน่ง. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | ข้อมูลการแยกส่วนแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนแบบกำหนดเอง. มี data point ที่จะวาดในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | ระบุค่าที่จะใช้กำหนดว่า data point ใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | บ่งบอกว่าชุด series ของกลุ่มนี้ถูกวาดบนแกนรอง. อ่านอย่างเดียว **bool**. |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | ส่งคืนคอลเลกชันของ series. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/). |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | ส่งคืนประเภทของกลุ่ม series นี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../combinableseriestypesgroup/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | ให้การเข้าถึงแท่ง up/down ของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../iupdownbarsmanager/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้างแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. อานาล็อกของโอเปอร์เรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกข้อมูลใด ๆ เพียงแต่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกข้อมูลใด ๆ เพียงแต่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | สเปเชียลไลเซชันของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | สเปเชียลไลเซชันของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแบบแชร์ลงตามค่าที่ระบุ. |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิฟอง. เขียน [BubbleSizeRepresentationType](../bubblesizerepresentationtype/). |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | ระบุค่าสเกลแฟกเตอร์สำหรับแผนภูมิฟอง (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). เขียน **int32_t**. |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | ระบุขนาดของรูในแผนภูมิดอนัท (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). เขียน **uint8_t**. |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | กำหนดองศาของชิ้นแรกของพายหรือดอนัท (ตามเข็มนาฬิกาจากด้านบน, จาก 0 ถึง 360 องศา). เขียน **uint16_t**. |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | กำหนดระยะเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์ระหว่าง series ของข้อมูลในแผนภูมิ 3 มิติ. เขียน **uint16_t**. |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. เขียน **uint16_t**. |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | เป็นจริงหากแผนภูมิมีเส้น series. ใช้กับแผนภูมิแท่งซ้อนและ OfPie. เขียน **bool**. |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวใน series มีสีต่างกัน. เขียน **bool**. |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | ระบุเปอร์เซ็นต์การทับซ้อนของแท่งและคอลัมน์บนแผนภูมิ 2 มิติ (จาก -100% ถึง 100%). |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | ระบุวิธีการกำหนดว่า data point ใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. เขียน [PieSplitType](../piesplittype/). |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | ระบุค่าที่จะใช้กำหนดว่า data point ใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับ property PieSplitBy. เขียน **double**. |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). เขียน **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument ที่ n ของเทมเพลตเป็น weak pointer (แทน shared). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบแชร์และส่งค่ากลับ. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของ series มีคุณสมบัติบางอย่างของ series ที่เป็นสาธารณะสำหรับ series แต่ละตัวในกลุ่ม ("series group properties"). "Series group properties" ในคลาส [ChartSeriesGroup](./) เป็นแบบอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส [ChartSeries](../chartseries/).

## ดูเพิ่มเติม

* คลาส [IChartSeriesGroup](../ichartseriesgroup/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)