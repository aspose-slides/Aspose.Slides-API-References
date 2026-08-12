---
title: IChartSeries
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงชุดข้อมูลแผนภูมิ.
type: docs
weight: 820
url: /th/aspose.slides.charts/ichartseries/
---
## IChartSeries คลาส

Represents a chart series.

```cpp
class IChartSeries : public Aspose::Slides::Charts::IChartComponent
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าทั้งหมด รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าทั้งหมด รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [ChartShapeType](../chartshapetype/) [get_Bar3DShape](./get_bar3dshape/)() | ระบุรูปร่างของชุดข้อมูลในแผนภูมิแท่ง 3 มิติ การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ อ่าน [ChartShapeType](../chartshapetype/). |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | ระบุว่าค่าขนาดฟองบนแผนภูมิบับเบิลจะแสดงอย่างไร นี่เป็นคุณสมบัติของชุดข้อมูลนี้และของชุดข้อมูลทั้งหมดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติของกลุ่มที่เหมาะสม และดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeRepresentation() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | ระบุตัวคูณสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น) นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_BubbleSizeScale() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | คืนค่าแผนภูมิ. อ่านอย่างเดียว [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_DataPoint](./get_datapoint/)(**int32_t**) | คืนค่าจุดข้อมูลของชุดนี้ที่ตำแหน่งที่ระบุ. |
| virtual **int32_t** [get_DataPoint](./get_datapoint/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointCollection](../ichartdatapointcollection/)\> [get_DataPoints](./get_datapoints/)() | คืนค่าคอลเลกชันของจุดข้อมูลของชุดนี้. อ่านอย่างเดียว [IChartDataPointCollection](../ichartdatapointcollection/). |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | ระบุขนาดของรูรอบแถบในแผนภูมโดนัท (สามารถอยู่ระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต) นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_DoughnutHoleSize() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **uint8_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsXFormat](./get_errorbarsxformat/)() | แสดง ErrorBars ของชุดข้อมูลที่มีทิศทาง X. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsFormat](../ierrorbarsformat/)\> [get_ErrorBarsYFormat](./get_errorbarsyformat/)() | แสดง ErrorBars ของชุดข้อมูลที่มีทิศทาง Y. |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | ระยะของชิ้นพายเปิดจากศูนย์กลางของแผนภูมิกับเป็นเปอร์เซ็นต์ของเส้นผ่าศูนย์กลางพาย. อ่าน **int32_t**. |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | ระบุมุมของชิ้นพายหรือโดนัทชิ้นแรก เป็นองศา (ตามเข็มนาฬิกาตั้งแต่ด้านบน, จาก 0 ถึง 360 องศ) นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_FirstSliceAngle() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **uint16_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | คืนรูปแบบของชุดข้อมูล. อ่านอย่างเดียว [IFormat](../iformat/). |
| virtual **int32_t** [get_GapDepth](./get_gapdepth/)() | คืนค่าระยะทางเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ ระหว่างชุดข้อมูลในแผนภูมิกับ 3D. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapDepth() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **int32_t**. |
| virtual **int32_t** [get_GapWidth](./get_gapwidth/)() | ระบุช่องว่างระหว่างกลุ่มแท่งหรือคอลัมน์ เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_GapWidth() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **int32_t**. |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | กำหนดว่ามีเส้นชุดข้อมูลสำหรับชุดนี้และชุดที่เกี่ยวข้องหรือไม่. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_HasSeriesLines() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. ใช้ ParentSeriesGroup.SeriesLinesFormat property สำหรับรูปแบบเส้นชุดข้อมูล. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_HasUpDownBars](./get_hasupdownbars/)() | กำหนดว่าแผนภูมิแบบเส้นหรือแถบมีแท่งขึ้น/ลงหรือไม่. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars()->get(set)_HasUpDownBars() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get_UpDownBars() property สำหรับรูปแบบแท่งขึ้น/ลง. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_InvertedSolidFillColor](./get_invertedsolidfillcolor/)() | ระบุสีทึบกลับด้านสำหรับชุดข้อมูล. เพื่อใช้การตั้งค่าสีตั้งค่า FillType ของรูปแบบชุดข้อมูลเป็น [FillType::Solid](../../aspose.slides/filltype/). อ่าน [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | ระบุว่าชุดแท่ง, คอลัมน์ หรือบับเบิลจะกลับสีเมื่อตัวค่าเป็นลบ. อ่าน **bool**. |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | ระบุว่ามาร์คเดทาแต่ละจุดในชุดมีสีที่แตกต่างกัน. นี่เป็นคุณสมบัติไม่เพียงของชุดข้อมูลนี้แต่ของทุกชุดข้อมูลในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_IsColorVaried() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)(**int32_t**) | คืนป้ายข้อมูลสำหรับจุดข้อมูลของชุดนี้ที่ตำแหน่งที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelCollection](../idatalabelcollection/)\> [get_Labels](./get_labels/)() | คืนป้ายกำกับของชุด. อ่านอย่างเดียว [IDataLabelCollection](../idatalabelcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | คืนมาร์คเกอร์ของชุด. อ่านอย่างเดียว [IMarker](../imarker/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringChartValue](../istringchartvalue/)\> [get_Name](./get_name/)() | คืนชื่อของชุด. อ่านอย่างเดียว [IStringChartValue](../istringchartvalue/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfBubbleSizes](./get_numberformatofbubblesizes/)() | คืนรูปแบบตัวเลขสำหรับขนาดบับเบิลของชุด. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfValues](./get_numberformatofvalues/)() | คืนรูปแบบตัวเลขสำหรับค่าของชุด. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfXValues](./get_numberformatofxvalues/)() | คืนรูปแบบตัวเลขสำหรับค่าตำแหน่ง x ของชุด. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_NumberFormatOfYValues](./get_numberformatofyvalues/)() | คืนรูปแบบตัวเลขสำหรับค่าตำแหน่ง y ของชุด. อ่าน [System::String](../../system/string/). |
| virtual **int32_t** [get_Order](./get_order/)() | คืนลำดับของชุด. อ่าน **int32_t**. |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | ระบุเปอร์เซ็นต์ที่แท่งและคอลัมน์ทับซ้อนบนแผนภูมิกับ 2-D (จาก -100% ถึง 100%). นี่เป็นคุณสมบัติไม่เพียงของชุดนี้แต่ของทุกชุดในกลุ่มชุดข้อมูลแม่ — การฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว เพื่อเปลี่ยนค่า ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_Overlap() คุณสมบัติอ่าน/เขียน. อ่านอย่างเดียว **int8_t**. |
| virtual [ParentLabelLayoutType](../parentlabellayouttype/) [get_ParentLabelLayout](./get_parentlabellayout/)() | แสดงการจัดวางของป้ายหมวดหมู่แม่. ใช้ได้เฉพาะกับแผนภูมิ Treemap. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](./)\> [get_ParentSeries](./get_parentseries/)(**int32_t**) | คืนชุดข้อมูลแผนภูมิในกลุ่มชุดข้อมูลแม่ที่ตำแหน่งที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_ParentSeriesGroup](./get_parentseriesgroup/)() | คืนกลุ่มชุดข้อมูลแม่. อ่านอย่างเดียว [IChartSeriesGroup](../ichartseriesgroup/). |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. นี่เป็นคุณสมบัติไม่เพียงของชุดนี้แต่ของทุกชุดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitBy() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว [PieSplitType](../piesplittype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. คืนจุดข้อมูลที่ต้องวาดในพายหรือแท่งที่สองที่ตำแหน่งที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ต้องวาดในพายหรือแท่งที่สอง. นี่เป็นคุณสมบัติไม่เพียงของชุดนี้แต่ของทุกชุดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่ม. อ่านอย่างเดียว [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/). |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | ระบุค่าที่ใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. นี่เป็นคุณสมบัติไม่เพียงของชุดนี้แต่ของทุกชุดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_PieSplitPosition() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **double**. |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | บ่งบอกว่าชุดนี้ถูกวาดบนแกนค่าที่สองหรือไม่. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual [QuartileMethodType](../quartilemethodtype/) [get_QuartileMethod](./get_quartilemethod/)() | แสดงวิธีควอร์ไทล. ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | แสดงรายการคำอธิบายที่เกี่ยวข้องกับชุดนี้. อ่านอย่างเดียว [ILegendEntryProperties](../ilegendentryproperties/). |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). นี่เป็นคุณสมบัติไม่เพียงของชุดนี้แต่ของทุกชุดในกลุ่มชุดข้อมูลแม่ — เป็นการฉายของคุณสมบัติที่เหมาะสมของกลุ่มและดังนั้นคุณสมบัตินี้เป็นแบบอ่านอย่างเดียว ใช้คุณสมบัติ ParentSeriesGroup เพื่อเข้าถึงกลุ่มชุดข้อมูลแม่ ใช้ [get_ParentSeriesGroup()](./get_parentseriesgroup/)->get(set)_SecondPieSize() คุณสมบัติอ่าน/เขียนเพื่อเปลี่ยนค่า. อ่านอย่างเดียว **uint16_t**. |
| virtual **bool** [get_ShowConnectorLines](./get_showconnectorlines/)() | แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะกับแผนภูมิ Waterfall. |
| virtual **bool** [get_ShowInnerPoints](./get_showinnerpoints/)() | แสดงจุดภายใน. จริงถ้าจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. อ่าน **bool**. |
| virtual **bool** [get_ShowMeanLine](./get_showmeanline/)() | แสดงเครื่องหมายค่าเฉลี่ย. จริงถ้าเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. อ่าน **bool**. |
| virtual **bool** [get_ShowMeanMarkers](./get_showmeanmarkers/)() | แสดงเครื่องหมายค่าเฉลี่ย. จริงถ้าเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. อ่าน **bool**. |
| virtual **bool** [get_ShowOutlierPoints](./get_showoutlierpoints/)() | แสดงจุดผิดปกติ. จริงถ้าจุดผิดปกติแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะกับแผนภูมิ BoxAndWhisker. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual **bool** [get_Smooth](./get_smooth/)() | แสดงการทำให้เส้นโค้งเรียบ. จริงถ้าการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือกระจาย. ใช้ได้เฉพาะกับแผนภูมิเส้นและกระจายที่เชื่อมต่อด้วยเส้น. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendline](../itrendline/)\> [get_TrendLine](./get_trendline/)(**int32_t**) | คืนเส้นแนวโน้มที่ตำแหน่งที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITrendlineCollection](../itrendlinecollection/)\> [get_TrendLines](./get_trendlines/)() | คอลเลกชันของเส้นแนวโน้มของชุดข้อมูล. อ่านอย่างเดียว [ITrendlineCollection](../itrendlinecollection/). |
| virtual [ChartType](../charttype/) [get_Type](./get_type/)() | คืนประเภทของชุดนี้. อ่าน [ChartType](../charttype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticSeriesColor](./getautomaticseriescolor/)() | คืนสีอัตโนมัติของชุดตามดัชนีชุดและสไตล์แผนภูมิ. สีนี้จะใช้เป็นค่าเริ่มต้นหาก FillType เท่ากับ NotDefined. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อานาล็อกของออปเปอเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง C# lock() เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนของประเภทที่กำหนดเอง. |
|   [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมายค่า. จริงๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| virtual void [set_Bar3DShape](./set_bar3dshape/)([ChartShapeType](../chartshapetype/)) | ระบุรูปร่างของชุดข้อมูลในแผนภูมิแท่ง 3 มิติ การเปลี่ยนค่าของคุณสมบัตินี้อาจทำให้ประเภทของชุดข้อมูลเปลี่ยนโดยอัตโนมัติ เขียน [ChartShapeType](../chartshapetype/). |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | ระยะของชิ้นพายเปิดจากศูนย์กลางของแผนภูมิกับเป็นเปอร์เซ็นต์ของเส้นผ่าศูนย์กลางพาย. เขียน **int32_t**. |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | ระบุว่าชุดแท่ง, คอลัมน์ หรือบับเบิลจะกลับสีเมื่อตัวค่าเป็นลบ. เขียน **bool**. |
| virtual void [set_NumberFormatOfBubbleSizes](./set_numberformatofbubblesizes/)([System::String](../../system/string/)) | ตั้งค่ารูปแบบตัวเลขสำหรับขนาดบับเบิลของชุด. เขียน [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfValues](./set_numberformatofvalues/)([System::String](../../system/string/)) | ตั้งค่ารูปแบบตัวเลขสำหรับค่าของชุด. เขียน [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfXValues](./set_numberformatofxvalues/)([System::String](../../system/string/)) | ตั้งค่ารูปแบบตัวเลขสำหรับค่าตำแหน่ง x ของชุด. เขียน [System::String](../../system/string/). |
| virtual void [set_NumberFormatOfYValues](./set_numberformatofyvalues/)([System::String](../../system/string/)) | ตั้งค่ารูปแบบตัวเลขสำหรับค่าตำแหน่ง y ของชุด. เขียน [System::String](../../system/string/). |
| virtual void [set_Order](./set_order/)(**int32_t**) | คืนลำดับของชุด. เขียน **int32_t**. |
| virtual void [set_ParentLabelLayout](./set_parentlabellayout/)([ParentLabelLayoutType](../parentlabellayouttype/)) | แสดงการจัดวางของป้ายหมวดหมู่แม่. ใช้ได้เฉพาะแผนภูมิ Treemap. |
| virtual void [set_PlotOnSecondAxis](./set_plotonsecondaxis/)(**bool**) | บ่งบอกว่าชุดนี้ถูกวาดบนแกนค่าที่สองหรือไม่. เขียน **bool**. |
| virtual void [set_QuartileMethod](./set_quartilemethod/)([QuartileMethodType](../quartilemethodtype/)) | แสดงวิธีควอร์ไทล. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. |
| virtual void [set_ShowConnectorLines](./set_showconnectorlines/)(**bool**) | แสดงเส้นเชื่อมต่อ. ใช้ได้เฉพาะแผนภูมิ Waterfall. |
| virtual void [set_ShowInnerPoints](./set_showinnerpoints/)(**bool**) | แสดงจุดภายใน. จริงถ้าจุดภายในแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| virtual void [set_ShowMeanLine](./set_showmeanline/)(**bool**) | แสดงเครื่องหมายค่าเฉลี่ย. จริงถ้าเส้นค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| virtual void [set_ShowMeanMarkers](./set_showmeanmarkers/)(**bool**) | แสดงเครื่องหมายค่าเฉลี่ย. จริงถ้าเครื่องหมายค่าเฉลี่ยแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| virtual void [set_ShowOutlierPoints](./set_showoutlierpoints/)(**bool**) | แสดงจุดผิดปกติ. จริงถ้าจุดผิดปกติแสดงบนแผนภูมิ BoxAndWhisker. ใช้ได้เฉพาะแผนภูมิ BoxAndWhisker. เขียน **bool**. |
| virtual void [set_Smooth](./set_smooth/)(**bool**) | แสดงการทำให้เส้นโค้งเรียบ. จริงถ้าการทำให้เส้นโค้งเรียบเปิดใช้งานสำหรับแผนภูมิเส้นหรือกระจาย. ใช้ได้เฉพาะกับแผนภูมิเส้นและกระจายที่เชื่อมต่อด้วยเส้น. เขียน **bool**. |
| virtual void [set_Type](./set_type/)([ChartType](../charttype/)) | คืนประเภทของชุดนี้. เขียน [ChartType](../charttype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง C# lock() เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยทุกโครงสร้างข้อมูลภายใน. |

## ดูเพิ่มเติม

* คลาส [IChartComponent](../ichartcomponent/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)