---
title: ChartSeries
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนชุดข้อมูลแผนภูมิ.
type: docs
weight: 274
url: /th/aspose.slides.charts/chartseries/
---
## คลาส ChartSeries

แทนชุดข้อมูลแผนภูมิ

```cpp
class ChartSeries : public Aspose::Slides::Charts::IChartSeries,
                    public Aspose::Slides::IDOMObject
```

## วิธีการ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้รูปแบบการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าโดย IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าโดย IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() override | ระบุรูปร่างของชุดข้อมูลในแผนภูมิแท่ง 3 มิติ การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ อ่าน [ChartShapeType](../chartshapetype/). |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | ระบุว่าค่าขนาดฟองของแผนภูมิฟองจะถูกแสดงอย่างไร ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | ระบุสเกลแฟกเตอร์สำหรับแผนภูมิฟอง (ค่าได้ระหว่าง 0-300% ของขนาดเริ่มต้น) ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | ส่งคืนแผนภูมิแม่ อ่านอย่างเดียว [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) override | ส่งคืนจุดข้อมูลของชุดนี้ที่ตำแหน่งที่ระบุ. |
| **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() override | ส่งคืนคอลเลกชันของจุดข้อมูลของชุดนี้. อ่านอย่างเดียว [IChartDataPointCollection](../ichartdatapointcollection/). |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | ระบุขนาดของรูในแผนภูมิลูกรูป (ค่าได้ระหว่าง 10-90% ของขนาดพื้นที่พล็อต) ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **uint8_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() override | แสดง ErrorBars ของชุดข้อมูลที่มีทิศทาง X. |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() override | แสดง ErrorBars ของชุดข้อมูลที่มีทิศทาง Y. |
| **int32_t** [get_Explosion](./get_explosion/)() override | ระยะห่างของชิ้นพายที่เปิดจากศูนย์กลางของแผนภูมิปายแสดงเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. อ่าน **int32_t**. |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | ระบุมุมของชิ้นพายหรือชิ้นโดนัทแรกในองศา (นาฬิการองจากบน, 0-360 องศ) ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **uint16_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | ส่งคืนรูปแบบของชุดข้อมูล. อ่านอย่างเดียว [IFormat](../iformat/). |
| **int32_t** [get_GapDepth](./get_gapdepth/)() override | ส่งคืนระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ระหว่างชุดข้อมูลในแผนภูมิ 3D ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **int32_t**. |
| **int32_t** [get_GapWidth](./get_gapwidth/)() override | ระบุช่องว่างระหว่างกลุ่มแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์ ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **int32_t**. |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | กำหนดว่ามีเส้นชุดข้อมูลสำหรับชุดข้อมูลนี้และชุดข้อมูลที่เกี่ยวข้องหรือไม่ ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. ใช้คุณสมบัติ ParentSeriesGroup.SeriesLinesFormat เพื่อจัดรูปแบบเส้นชุดข้อมูล. อ่านอย่างเดียว **bool**. |
| **bool** [get_HasUpDownBars](./get_hasupdownbars/)() override | กำหนดว่าแผนภูมิ Line หรือ Stock มีแถบขึ้น/ลงหรือไม่ ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() คุณสมบัติเพื่อจัดรูปแบบแถบขึ้น/ลง. อ่านอย่างเดียว **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() override | ระบุตัวเลือกสีทึบกลับสำหรับชุดข้อมูล เพื่อใช้การตั้งค่าสีให้ตั้ง FillType ของรูปแบบชุดข้อมูลเป็น [FillType::Solid](../../aspose.slides/filltype/). อ่าน [ColorFormat](../../aspose.slides/colorformat/). |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | ระบุว่าชุดข้อมูลแถบ คอลัมน์ หรือฟองควรกลับสีเมื่อค่าติดลบ. อ่าน **bool**. |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละจุดในชุดข้อมูลมีสีต่างกัน ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) override | ส่งคืนป้ายข้อมูลสำหรับจุดข้อมูลของชุดนี้ที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() override | ส่งคืน Labels ของชุดข้อมูล. อ่านอย่างเดียว [IDataLabelCollection](../idatalabelcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | [Marker](../marker/). อ่านอย่างเดียว [IMarker](../imarker/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() override | ส่งคืนชื่อชุดข้อมูล. อ่านอย่างเดียว [IStringChartValue](../istringchartvalue/). |
| [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() override | NumberFormatOfBubbleSizes. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() override | NumberFormatOfValues. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() override | NumberFormatOfXValues. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() override | NumberFormatOfYValues. อ่าน [System::String](../../system/string/). |
| **int32_t** [get_Order](./get_order/)() override | ส่งคืนลำดับของชุดข้อมูล. อ่าน **int32_t**. |
| **int8_t** [get_Overlap](./get_overlap/)() override | ระบุว่าบาร์และคอลัมน์ทับซ้อนบนแผนภูมิ 2-D เท่าใด เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%) ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ [get_ParentSeriesGroup()->Overlap()](./get_parentseriesgroup/) อ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **int8_t**. |
| [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() override | แสดงการจัดวางของป้ายหมวดหมู่แม่ ใช้เฉพาะแผนภูมิ Treemap. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) override | ส่งคืนชุดข้อมูลแผนภูมิในกลุ่มชุดข้อมูลแม่ที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() override | ParentSeriesGroup. อ่านอย่างเดียว [IChartSeriesGroup](../ichartseriesgroup/). |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม และคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว [PieSplitType](../piesplittype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | ข้อมูลแยกกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกกำหนดเอง ส่งคืนจุดข้อมูลที่ควรวาดในพายหรือแถบที่สองที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | ข้อมูลแยกกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกกำหนดเอง ประกอบด้วยจุดข้อมูลที่ควรวาดในพายหรือแถบที่สอง ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม อ่านอย่างเดียว [PieSplitCustomPointCollection](../piesplitcustompointcollection/). |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | ระบุค่าที่ใช้เพื่อกำหนดว่าข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie ใช้ร่วมกับคุณสมบัติ PieSplitBy ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **double**. |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | ระบุว่าชุดข้อมูลนี้ถูกวางบนแกนรองหรือไม่. อ่าน **bool**. |
| [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() override | แสดงวิธีการควอไทล์ ใช้เฉพาะแผนภูมิ BoxAndWhisker. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | แสดงรายการคำอธิบายที่เกี่ยวข้องกับชุดข้อมูลนี้ อ่านอย่างเดียว [ILegendEntryProperties](../ilegendentryproperties/). |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (ค่าได้ระหว่าง 5-200%) ซึ่งเป็นคุณสมบัติของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติกลุ่มที่เหมาะสม ดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **uint16_t**. |
| **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() override | แสดงเส้นเชื่อมต่อ ใช้เฉพาะแผนภูมิ Waterfall. |
| **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() override | แสดงจุดในกรอบ ในกรณี BoxAndWhisker ถ้าจะแสดงจุดในกรอบ อ่าน **bool**. |
| **bool** [get_ShowMeanLine](./get_showmeanline/)() override | แสดงเส้นค่าเฉลี่ย ในกรณี BoxAndWhisker ถ้าจะแสดงเส้นค่าเฉลี่ย อ่าน **bool**. |
| **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() override | แสดงสัญลักษณ์ค่าเฉลี่ย ในกรณี BoxAndWhisker ถ้าจะแสดงสัญลักษณ์ค่าเฉลี่ย อ่าน **bool**. |
| **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() override | แสดงจุดหลุดออก ในกรณี BoxAndWhisker ถ้าจะแสดงจุดหลุดออก อ่าน **bool**. |
| **bool** [get_Smooth](./get_smooth/)() override | แสดงการทำให้เส้นโค้งเรียบ ในกรณีแผนภูมิเส้นหรือกระจายที่เชื่อมต่อด้วยเส้น ถ้าเปิดใช้งาน อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) override | ส่งคืนเส้นแนวโน้มที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() override | คอลเลกชันของเส้นแนวโน้มชุดข้อมูล. อ่านอย่างเดียว [ITrendlineCollection](../itrendlinecollection/). |
| [ChartType](../charttype/) [get_Type](./get_type/)() override | ส่งคืนประเภทของชุดข้อมูลนี้. อ่าน [ChartType](../charttype/). |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() override | ส่งคืนสีอัตโนมัติของชุดข้อมูลตามดัชนีชุดข้อมูลและสไตล์แผนภูมิ สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อทำ lock. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) override | ระบุรูปร่างของชุดข้อมูลในแผนภูมิแท่ง 3 มิติ การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ เขียน [ChartShapeType](../chartshapetype/). |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | ระยะห่างของชิ้นพายที่เปิดจากศูนย์กลางของแผนภูมิปายเป็นเปอร์เซ็นต์ของเส้นผ่านศูนย์กลางพาย. เขียน **int32_t**. |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | ระบุว่าชุดข้อมูลแถบ คอลัมน์ หรือฟองควรกลับสีเมื่อค่าติดลบ. เขียน **bool**. |
| void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) override | NumberFormatOfBubbleSizes. เขียน [System::String](../../system/string/). |
| void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) override | NumberFormatOfValues. เขียน [System::String](../../system/string/). |
| void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) override | NumberFormatOfXValues. เขียน [System::String](../../system/string/). |
| void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) override | NumberFormatOfYValues. เขียน [System::String](../../system/string/). |
| void [set_Order](./set_order/)(**int32_t**) override | ส่งคืนลำดับของชุดข้อมูล. เขียน **int32_t**. |
| void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) override | แสดงการจัดวางของป้ายหมวดหมู่แม่ ใช้เฉพาะแผนภูมิ Treemap. |
| void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) override | ระบุว่าชุดข้อมูลนี้ถูกวางบนแกนรองหรือไม่. เขียน **bool**. |
| void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) override | แสดงวิธีการควอไทล์ ใช้เฉพาะแผนภูมิ BoxAndWhisker. |
| void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) override | แสดงเส้นเชื่อมต่อ ใช้เฉพาะแผนภูมิ Waterfall. |
| void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) override | แสดงจุดในกรอบ หากแสดงจุดในกรอบบนแผนภูมิ BoxAndWhisker ใช้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| void [set_ShowMeanLine](./set_showmeanline/)(**bool**) override | แสดงเส้นค่าเฉลี่ย หากแสดงเส้นค่าเฉลี่ยบนแผนภูมิ BoxAndWhisker ใช้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) override | แสดงสัญลักษณ์ค่าเฉลี่ย หากแสดงสัญลักษณ์ค่าเฉลี่ยบนแผนภูมิ BoxAndWhisker ใช้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) override | แสดงจุดหลุดออก หากแสดงจุดหลุดออกบนแผนภูมิ BoxAndWhisker ใช้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| void [set_Smooth](./set_smooth/)(**bool**) override | แสดงการทำให้เส้นโค้งเรียบ หากเปิดการทำให้เส้นโค้งเรียบบนแผนภูมิเส้นหรือกระจายที่เชื่อมต่อด้วยเส้น ใช้เฉพาะแผนภูมิ เส้นและกระจายที่เชื่อมต่อด้วยเส้น. เขียน **bool**. |
| void [set_Type](./set_type/)([ChartType](../charttype/)) override | ส่งคืนประเภทของชุดข้อมูลนี้. เขียน [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งกลับค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IChartSeries](../ichartseries/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)