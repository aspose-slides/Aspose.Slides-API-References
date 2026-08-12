---
title: BaseEnumerator
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คำนิยาม Enumerator เพื่อห่อหุ้มประเภทที่มีรูปแบบเหมือน STL สำหรับการใช้งานแบบ C#. ไม่ได้ทำการอ้างอิงโครงสร้างของคอนเทนเนอร์ยกเว้นการมี iterator แบบต่อเนื่อง ใช้ฟังก์ชัน begin() และ end() วัตถุของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการล้มเหลวของการตรวจสอบ ควรห่อหุ้มคลาสนี้ด้วยตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 66
url: /th/system.collections.generic/baseenumerator/
---
## BaseEnumerator คลาส


Enumerator definition to wrap STL-styled types for C#-styled usage. Makes no assertions on container structure except for existance of sequental iterator. Uses begin() and end() functions. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename Container,typename Element>class BaseEnumerator : public System::Collections::Generic::IEnumerator<Element>
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Container | STL-styled container type. |
| Element | Element type. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [IEnumerator](../ienumerator/) * [AsVirtualizedIterator](../ienumerator/asvirtualizediterator/)() | เตรียม iterator เพื่อใช้โดยคลาส VirtualizedIterator. |
| [BaseEnumerator](./baseenumerator/)(const [Object::ptr](../../system/object/ptr/)\&, Container\&) | เริ่มต้น iterator. |
| System::Details::VirtualizedIteratorBase\<T\> * [CloneIterator](../ienumerator/cloneiterator/)() const override | ทำสำเนา iterator ปัจจุบัน. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [Current](../ienumerator/current/)() const | รับ element ปัจจุบัน. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | ไม่ทำอะไร. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# สำหรับ double โดย NaN สองค่าเป็นเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual [MakeConstRef_t](../../system/makeconstref_t/)\<T\> [get_Current](../ienumerator/get_current/)() const | รับ element ปัจจุบัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุนั้น. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของวัตถุ. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [IEnumerator](../ienumerator/ienumerator/)() |  |
| void [IncrementIterator](../ienumerator/incrementiterator/)() override | เลื่อน iterator ไปข้างหน้าหนึ่งขั้น. |
| void [InitializeIterator](../ienumerator/initializeiterator/)() override | ทำการเรียก [MoveNext()](../ienumerator/movenext/) ครั้งแรกและเตรียมวัตถุ enumerator เพื่อใช้โดย VirtualizedIterator. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| **bool** [IsValid](./isvalid/)() const | ตรวจสอบว่า [MoveNext()](./movenext/) ถูกเรียกและยังไม่ถึงจุดสิ้นสุด. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| void [MarkOwnedByVirtualizedIterator](../ienumerator/markownedbyvirtualizediterator/)() | ทำเครื่องหมาย enumerator ที่เป็นของ virtualized iterator. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
| **bool** [MoveNext](./movenext/)() override | การเพิ่มแบบ enumerator. |
| [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การมอบหมายค่า. ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของวัตถุแบบค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่า shared reference count ลงตามค่าที่ระบุ. |
| void [Reset](./reset/)() override | รีเซ็ต enumerator เพื่อให้สามารถทำ enumerating ใหม่ของ elements. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของ shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | จำลองการสร้าง C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~IEnumerator](../ienumerator/~ienumerator/)() |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IEnumerator](../ienumerator/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)