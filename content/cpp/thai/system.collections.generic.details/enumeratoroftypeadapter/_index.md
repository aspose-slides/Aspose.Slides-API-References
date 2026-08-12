---
title: EnumeratorOfTypeAdapter
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: Enumerator ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.OfType()
type: docs
weight: 66
url: /th/system.collections.generic.details/enumeratoroftypeadapter/
---
## EnumeratorOfTypeAdapter คลาส

Enumerator ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.OfType() extension method.

```cpp
template<typename Source,typename Result>class EnumeratorOfTypeAdapter : public System::Collections::Generic::IEnumerator<Result>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Source | ประเภทต้นทางขององค์ประกอบในคอลเลกชัน |
| Result | ประเภทผลลัพธ์ขององค์ประกอบในคอลเลกชัน |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [IEnumerator](../../system.collections.generic/ienumerator/) * [AsVirtualizedIterator](../../system.collections.generic/ienumerator/asvirtualizediterator/)() | เตรียม iterator เพื่อใช้โดย VirtualizedIterator คลาส. |
| System::Details::VirtualizedIteratorBase\<Result\> * [CloneIterator](./cloneiterator/)() const override |  |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../../system.collections.generic/ienumerator/current/)() const | รับองค์ประกอบปัจจุบัน. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | ไม่ทำอะไร. |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/)([SharedPtr](../../system/sharedptr/)\<[IEnumerator](../../system.collections.generic/ienumerator/)\<Source\>\>) |  |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [MakeConstRef_t](../../system/makeconstref_t/)\<Result\> [get_Current](./get_current/)() const override | รับองค์ประกอบปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อเนกปรานของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของวัตถุ. อเนกปรานของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [IEnumerator](../../system.collections.generic/ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../../system.collections.generic/ienumerator/incrementiterator/)() override | เลื่อน iterator หนึ่งขั้นไปข้างหน้า. |
| void [InitializeIterator](../../system.collections.generic/ienumerator/initializeiterator/)() override | ทำการเรียก [MoveNext()](../../system.collections.generic/ienumerator/movenext/) ครั้งแรกและเตรียมวัตถุ enumerator เพื่อใช้โดย VirtualizedIterator |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. อเนกปรานของโอเปอร์เตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| void [MarkOwnedByVirtualizedIterator](../../system.collections.generic/ienumerator/markownedbyvirtualizediterator/)() | ทำเครื่องหมาย enumerator ที่เป็นของ virtualized iterator |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกปรานของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
| **bool** [MoveNext](./movenext/)() override | เลื่อน enumerator ไปยังองค์ประกอบถัดไป. หากไม่มีองค์ประกอบใดถูกอ้างอิงก่อนหน้านี้ จะตั้งค่าอ้างอิงไปยังองค์ประกอบแรกที่มี. หากถึงจุดสิ้นสุดของคอนเทนเนอร์ จะไม่ทำอะไร. |
| [Object](../../system/object/object/)() |  |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่คัดลอกอะไรเลย จริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. ไม่คัดลอกอะไรเลย จริง ๆ เพียงแค่เริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุแบบค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [Reset](./reset/)() override | รีเซ็ต enumerator ไปยังตำแหน่งก่อนองค์ประกอบแรก |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์ template ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกปรานของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็น string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [~IEnumerator](../../system.collections.generic/ienumerator/~ienumerator/)() |  |
| virtual [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IEnumerator](../../system.collections.generic/ienumerator/)
* เนมส페ซ [System::Collections::Generic::Details](../)
* ไลบรารี [Aspose.Slides](../../)