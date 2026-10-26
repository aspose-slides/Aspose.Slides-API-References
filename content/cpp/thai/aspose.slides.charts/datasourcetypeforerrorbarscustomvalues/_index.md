---
title: DataSourceTypeForErrorBarsCustomValues
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ระบุประเภทของค่าในรายการคุณสมบัติ ChartDataPoint::get_ErrorBarsCustomValues"
type: docs
weight: 404
url: /th/aspose.slides.charts/datasourcetypeforerrorbarscustomvalues/
---
## DataSourceTypeForErrorBarsCustomValues คลาส

ระบุประเภทของค่าในรายการคุณสมบัติ [ChartDataPoint::get_ErrorBarsCustomValues](../chartdatapoint/get_errorbarscustomvalues/)

```cpp
class DataSourceTypeForErrorBarsCustomValues : public Aspose::Slides::Charts::IDataSourceTypeForErrorBarsCustomValues
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [DataSourceTypeForErrorBarsCustomValues](./datasourcetypeforerrorbarscustomvalues/)() |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมสไตล์ C# ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่า ตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ XMinus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. อ่าน [DataSourceType](../datasourcetype/) |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ XPlus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. อ่าน [DataSourceType](../datasourcetype/) |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ YMinus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. อ่าน [DataSourceType](../datasourcetype/) |
| [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ YPlus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. อ่าน [DataSourceType](../datasourcetype/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอบบางอย่าง, เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอบบางอย่าง, เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมลงด้วยค่าที่ระบุ |
| void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ XMinus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPoint.ErrorBarsCustomValues.XMinus.Data. เขียน [DataSourceType](../datasourcetype/) |
| void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ XPlus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPoint.ErrorBarsCustomValues.XPlus.Data. เขียน [DataSourceType](../datasourcetype/) |
| void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ YMinus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data. เขียน [DataSourceType](../datasourcetype/) |
| void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) override | ระบุว่าคุณสมบัติ AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็นค่าจริงในวัตถุคุณสมบัติ YPlus ของจุดข้อมูลสำหรับค่าที่กำหนดเองของ error bars. กล่าวอีกนัยหนึ่ง มันระบุประเภทของค่าของคุณสมบัติ ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data. เขียน [DataSourceType](../datasourcetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ควรไม่ได้เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ควรไม่ได้เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิง weak. ควรไม่ได้เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิง weak. ควรไม่ได้เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IDataSourceTypeForErrorBarsCustomValues](../idatasourcetypeforerrorbarscustomvalues/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)