---
title: ChartData
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เป็นข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ.
type: docs
weight: 118
url: /th/aspose.slides.charts/chartdata/
---
## ChartData คลาส

เป็นข้อมูลที่ใช้สำหรับการพล็อตแผนภูมิ.

```cpp
class ChartData : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::Chart>>,
                  public Aspose::Slides::Charts::IChartData
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point สไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point สไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_Categories](./get_categories/)() override | รับหมวดหมู่หลัก (หรือทั้งหมวดหมู่หลักและรองหาก [ChartData::set_UseSecondaryCategories](./set_usesecondarycategories/) ตั้งค่าเป็น false) อ่านอย่างเดียว [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_Category](./get_category/)(**int32_t**) override | ส่งกลับหมวดหมู่หลักที่ตำแหน่งที่ระบุ หาก [get_UseSecondaryCategories](./get_usesecondarycategories/) เป็น false จะรับจากหมวดหมู่ทั้งหมด. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorkbook](../ichartdataworkbook/)\> [get_ChartDataWorkbook](./get_chartdataworkbook/)() override | รับโรงงานเซลล์เพื่อสร้างเซลล์ที่ใช้สำหรับซีรีส์หรือหมวดหมู่ของแผนภูมิ อ่านอย่างเดียว [IChartDataWorkbook](../ichartdataworkbook/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | ส่งกลับซีรีส์ที่ตำแหน่งที่ระบุ. |
| [ChartDataSourceType](../chartdatasourcetype/) [get_DataSourceType](./get_datasourcetype/)() override | แทนเส้นทางไฟล์ workbook ภายนอกหากเป็นแหล่งข้อมูลภายนอก, มิฉะนั้นเป็น null |
| [WorkbookType](../workbooktype/) [get_EmbeddedWorkbookType](./get_embeddedworkbooktype/)() override | รับประเภทของ workbook ที่ฝังอยู่ หาก [ChartData::get_DataSourceType](./get_datasourcetype/) เป็น [ChartDataSourceType::ExternalWorkbook](../chartdatasourcetype/) จะคืนค่า [WorkbookType::NotDefined](../workbooktype/). อ่านอย่างเดียว [WorkbookType](../workbooktype/). |
| [System::String](../../system/string/) [get_ExternalWorkbookPath](./get_externalworkbookpath/)() override | แทนแหล่งข้อมูลของแผนภูมิ |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategoryCollection](../ichartcategorycollection/)\> [get_SecondaryCategories](./get_secondarycategories/)() override | รับหมวดหมู่รองหาก [ChartData::get_UseSecondaryCategories](./get_usesecondarycategories/) เป็น true. อ่านอย่างเดียว [IChartCategoryCollection](../ichartcategorycollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartCategory](../ichartcategory/)\> [get_SecondaryCategory](./get_secondarycategory/)(**int32_t**) override | ส่งกลับหมวดหมู่รองที่ตำแหน่งที่ระบุ หาก [get_UseSecondaryCategories](./get_usesecondarycategories/) เป็น false แล้ว [ChartData::get_SecondaryCategories](./get_secondarycategories/) จะเป็น null. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesCollection](../ichartseriescollection/)\> [get_Series](./get_series/)() override | รับซีรีส์. อ่านอย่างเดียว [IChartSeriesCollection](../ichartseriescollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)([System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\>) override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroup](../ichartseriesgroup/)\> [get_SeriesGroup](./get_seriesgroup/)(**int32_t**) override | ส่งกลับกลุ่มของซีรีส์ที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesGroupCollection](../ichartseriesgroupcollection/)\> [get_SeriesGroups](./get_seriesgroups/)() override | รับกลุ่มของซีรีส์. อ่านอย่างเดียว [IChartSeriesGroupCollection](../ichartseriesgroupcollection/). |
| **bool** [get_UseSecondaryCategories](./get_usesecondarycategories/)() override | หากตั้งค่าเป็น false แล้ว [ChartData::get_SecondaryCategories](./get_secondarycategories/) จะคืนค่า null และข้อมูลใน [ChartData::get_Categories](./get_categories/) จะใช้ทั้งสำหรับซีรีส์หลักและรอง หากตั้งค่าเป็น true แล้วข้อมูลใน [ChartData::get_SecondaryCategories](./get_secondarycategories/) จะใช้สำหรับซีรีส์รองและข้อมูลใน [ChartData::get_Categories](./get_categories/) จะใช้สำหรับซีรีส์หลัก. อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| [System::String](../../system/string/) [GetRange](./getrange/)() override | รับช่วงข้อมูลแผนภูมิ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกการก่อสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกการก่อสร้างซับคลาส. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\> [ReadWorkbookStream](./readworkbookstream/)() override | เขียน workbook [Excel](../../aspose.slides.excel/) ที่บรรจุภายในลงในสตรีมในหน่วยความจำ. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr ด้วยการอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงแบบ shared ลงตามค่าที่ระบุ. |
| void [set_UseSecondaryCategories](./set_usesecondarycategories/)(**bool**) override | หากตั้งค่าเป็น false แล้ว [ChartData::get_SecondaryCategories](./get_secondarycategories/) จะคืนค่า null และข้อมูลใน [ChartData::get_Categories](./get_categories/) จะใช้ทั้งสำหรับซีรีส์หลักและรอง หากตั้งค่าเป็น true แล้วข้อมูลใน [ChartData::get_SecondaryCategories](./get_secondarycategories/) จะใช้สำหรับซีรีส์รองและข้อมูลใน [ChartData::get_Categories](./get_categories/) จะใช้สำหรับซีรีส์หลัก. เขียน **bool**. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/)) override | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. ข้อมูล [Chart](../chart/) จะถูกอัปเดตจาก workbook เป้าหมาย. |
| void [SetExternalWorkbook](./setexternalworkbook/)([System::String](../../system/string/), **bool**) override | ตั้งค่า workbook ภายนอกเป็นแหล่งข้อมูลสำหรับแผนภูมิ. |
| void [SetRange](./setrange/)([System::String](../../system/string/)) override | ตั้งค่าช่วงข้อมูลของแผนภูมิ. ซีรีส์และหมวดหมู่จะอัปเดตตามช่วงข้อมูลใหม่. หากจำนวนซีรีส์ในช่วงข้อมูลมากกว่าจำนวนซีรีส์ในข้อมูลแผนภูมิ จะเพิ่มซีรีส์เพิ่มเติมที่มีประเภทเดียวกับซีรีส์สุดท้ายในคอลเลกชันปัจจุบันไปที่ส่วนท้ายของคอลเลกชัน. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบ shared. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงแบบ shared และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [SwitchRowColumn](./switchrowcolumn/)() override | สลับข้อมูลตามแกน. ข้อมูลที่กำลังทำแผนภูมิสอดบนแกน X จะย้ายไปยังแกน Y และในทางกลับกัน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการคอนสตรัคท์ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WriteWorkbookStream](./writeworkbookstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::MemoryStream](../../system.io/memorystream/)\>) override | เริ่มต้น workbook [Excel](../../aspose.slides.excel/) ที่บรรจุภายในด้วยค่าที่ผู้ใช้ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DomObject](../../aspose.slides/domobject/)
* คลาส [IChartData](../ichartdata/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)