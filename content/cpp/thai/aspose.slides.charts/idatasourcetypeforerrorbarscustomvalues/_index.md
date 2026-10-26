---
title: IDataSourceTypeForErrorBarsCustomValues
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ระบุประเภทของค่าที่อยู่ในรายการคุณสมบัติ ChartDataPoint.ErrorBarsCustomValues
type: docs
weight: 976
url: /th/aspose.slides.charts/idatasourcetypeforerrorbarscustomvalues/
---
## IDataSourceTypeForErrorBarsCustomValues คลาส

ระบุประเภทของค่าในรายการคุณสมบัติ ChartDataPoint.ErrorBarsCustomValues

```cpp
class IDataSourceTypeForErrorBarsCustomValues : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ลักษณะการทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตัวสไตล์ C# ซึ่ง NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตัวสไตล์ C# ซึ่ง NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXMinusValues](./get_datasourcetypeforxminusvalues/)() | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property XMinus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPoint.ErrorBarsCustomValues.XMinus.Data อ่าน [DataSourceType](../datasourcetype/) |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForXPlusValues](./get_datasourcetypeforxplusvalues/)() | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property XPlus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPoint.ErrorBarsCustomValues.XPlus.Data อ่าน [DataSourceType](../datasourcetype/) |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYMinusValues](./get_datasourcetypeforyminusvalues/)() | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property YMinus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data อ่าน [DataSourceType](../datasourcetype/) |
| virtual [DataSourceType](../datasourcetype/) [get_DataSourceTypeForYPlusValues](./get_datasourcetypeforyplusvalues/)() | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property YPlus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data อ่าน [DataSourceType](../datasourcetype/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ซึ่งเปิดใช้งานการแฮชวัตถุแบบกำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของวัตถุ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นอเนกประสงค์ของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ซึ่งเปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงโดยค่าที่ระบุ |
| virtual void [set_DataSourceTypeForXMinusValues](./set_datasourcetypeforxminusvalues/)([DataSourceType](../datasourcetype/)) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property XMinus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPoint.ErrorBarsCustomValues.XMinus.Data เขียน [DataSourceType](../datasourcetype/) |
| virtual void [set_DataSourceTypeForXPlusValues](./set_datasourcetypeforxplusvalues/)([DataSourceType](../datasourcetype/)) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property XPlus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPoint.ErrorBarsCustomValues.XPlus.Data เขียน [DataSourceType](../datasourcetype/) |
| virtual void [set_DataSourceTypeForYMinusValues](./set_datasourcetypeforyminusvalues/)([DataSourceType](../datasourcetype/)) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property YMinus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPointEx.ErrorBarsCustomValues.YMinus.Data เขียน [DataSourceType](../datasourcetype/) |
| virtual void [set_DataSourceTypeForYPlusValues](./set_datasourcetypeforyplusvalues/)([DataSourceType](../datasourcetype/)) | ระบุว่า property AsCell หรือ AsLiteralString หรือ AsLiteralDouble เป็น property ที่ใช้งานได้ในวัตถุ property YPlus ของจุดข้อมูลสำหรับค่ากำหนดเองของ error bars หรือไม่ โดยสรุปจะระบุประเภทของค่าของ property ChartDataPointEx.ErrorBarsCustomValues.YPlus.Data เขียน [DataSourceType](../datasourcetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) ซึ่งอนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ควรไม่ได้เรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์ ควรไม่ได้เรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ซึ่งเปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference ควรไม่ได้เรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference ควรไม่ได้เรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)