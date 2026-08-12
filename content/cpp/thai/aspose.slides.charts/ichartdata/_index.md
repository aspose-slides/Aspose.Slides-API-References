---
title: IChartData
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.
type: docs
weight: 651
url: /th/aspose.slides.charts/ichartdata/
---
## IChartData คลาส

แสดงถึงข้อมูลที่ใช้สำหรับการวาดแผนภูมิ.

```cpp
class IChartData : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ C# ที่มี NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยที่เป็น double ตามสไตล์ C# ที่มี NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() | ดึงประเภทหลัก (หรือประเภทหลักและรองทั้งสองถ้า [IChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) ถูกตั้งค่าเป็น false). อ่านอย่างเดียว [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) | คืนค่าประเภทหลักที่ตำแหน่งที่ระบุ. หาก [get_UseSecondaryCategories](./get_usesecondarycategories/) เป็น false, จะดึงจากทุกประเภท. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() | ดึงโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับชุดข้อมูลแผนภูมิหรือประเภท. อ่านอย่างเดียว [IChartDataWorkbook](../ichartdataworkbook/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | คืนค่าซีรีส์ที่ตำแหน่งที่ระบุ. |
| virtual [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() | แสดงแหล่งข้อมูลของแผนภูมิ |
| virtual [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() | ดึงประเภทของเวิร์กบุ๊คฝัง. คืนค่า [WorkbookType::NotDefined](../workbooktype/) หาก [IChartData::get_DataSourceType](./get_datasourcetype/) เป็น [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/). อ่านอย่างเดียว [WorkbookType](../workbooktype/). |
| virtual [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() | แสดงพาธของเวิร์กบุ๊คภายนอกหากแหล่งข้อมูลเป็นภายนอก, มิฉะนั้นเป็น null |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() | ดึงประเภทรองหาก [IChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../ichartcategorycollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) | คืนค่าประเภทรองที่ตำแหน่งที่ระบุ. หาก [get_UseSecondaryCategories](./get_usesecondarycategories/) เป็น false, แล้ว [IChartData::get_SecondaryCategories](./get_secondarycategories/) จะเป็น null. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() | ดึงซีรีส์. อ่านอย่างเดียว [IChartSeriesCollection](../ichartseriescollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) |  |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) | คืนค่ากลุ่มของซีรีส์ที่ตำแหน่งที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() | ดึงกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| virtual **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() | หากตั้งค่าเป็น false แล้ว [IChartData::get_SecondaryCategories](./get_secondarycategories/) จะคืนค่า null และข้อมูลใน [IChartData::get_Categories](./get_categories/) จะใช้ทั้งสำหรับซีรีส์หลักและรอง. หากตั้งค่าเป็น true แล้วข้อมูลใน [IChartData::get_SecondaryCategories](./get_secondarycategories/) จะใช้สำหรับซีรีส์รองและข้อมูลใน [IChartData::get_Categories](./get_categories/) จะใช้สำหรับซีรีส์หลัก. อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual [System::String](../../system/string/) [GetRange](./getrange/)() | ดึงช่วงข้อมูลของแผนภูมิ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตรนด์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() | เขียนเวิร์กบุ๊ค [Excel](../../aspose.slides.excel/) ที่บรรจุภายในลงสตรีมในหน่วยความจำ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแยกพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแยกพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) | หากตั้งค่าเป็น false แล้ว [IChartData::get_SecondaryCategories](./get_secondarycategories/) จะคืนค่า null และข้อมูลใน [IChartData::get_Categories](./get_categories/) จะใช้ทั้งสำหรับซีรีส์หลักและรอง. หากตั้งค่าเป็น true แล้วข้อมูลใน [IChartData::get_SecondaryCategories](./get_secondarycategories/) จะใช้สำหรับซีรีส์รองและข้อมูลใน [IChartData::get_Categories](./get_categories/) จะใช้สำหรับซีรีส์หลัก. เขียน **bool**. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) | ตั้งเวิร์กบุ๊คภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูล [Chart](../chart/) จะอัปเดตจากเวิร์กบุ๊คเป้าหมาย. |
| virtual void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) | ตั้งเวิร์กบุ๊คภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| virtual void [SetRange](./setrange/)([System::String](../../system/string/)) | ตั้งช่วงข้อมูลของแผนภูมิ. ซีรีส์และประเภทจะอัปเดตตามช่วงข้อมูลใหม่. หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลแผนภูมิ จะเพิ่มซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์ล่าสุดในคอลเลกชันปัจจุบันที่ส่วนท้ายของคอลเลกชัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual void [SwitchRowColumn](./switchrowcolumn/)() | สลับข้อมูลตามแกน. ข้อมูลที่แสดงบนแกน X จะย้ายไปแกน Y และกลับกัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) | เริ่มต้นเวิร์กบุ๊ค [Excel](../../aspose.slides.excel/) ที่บรรจุภายในด้วยค่าที่ผู้ใช้กำหนด. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)