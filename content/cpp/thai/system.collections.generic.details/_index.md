---
title: "System::Collections::Generic::Details"
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 352
url: /th/system.collections.generic.details/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [EnumerableAdapter](./enumerableadapter/) | Enumerable ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.Cast() และ IEnumerable.OfType() |
| [EnumerableSelectAdapter](./enumerableselectadapter/) | Enumerable ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.Select() |
| [EnumerableSelectIndexAdapter](./enumerableselectindexadapter/) |  |
| [EnumerableSelectManyAdapter](./enumerableselectmanyadapter/) |  |
| [EnumeratorCastAdapter](./enumeratorcastadapter/) | Enumerator ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.Cast() |
| [EnumeratorOfTypeAdapter](./enumeratoroftypeadapter/) | Enumerator ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.OfType() |
| [EnumeratorSelectAdapter](./enumeratorselectadapter/) | Enumerator ที่ใช้โดยเมธอดส่วนขยาย IEnumerable.Select() |
| [EnumeratorSelectIndexAdapter](./enumeratorselectindexadapter/) |  |
| [EnumeratorSelectManyAdapter](./enumeratorselectmanyadapter/) |  |
| [GroupEnumerable](./groupenumerable/) |  |
| [Grouping](./grouping/) |  |

## โครงสร้าง

| โครงสร้าง | คำอธิบาย |
| --- | --- |
| [ComparerType](./comparertype/) | เปรียบเทียบองค์ประกอบโดยใช้ semantics ‘less’ |
| [ComparerType< SharedPtr< T > >](./comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/) | เปรียบเทียบองค์ประกอบโดยใช้ semantics ‘less’ |
| [has_method_compareto](./has_method_compareto/) | ตรวจสอบว่ามีเมธอด CompareTo อยู่ในชนิดที่ระบุหรือไม่ หากมี จะสืบทอด std::true_type มิฉะนั้นสืบทอด std::false_type สามารถใช้ใน std::enable_if |
| [has_method_compareto_shared_ptr](./has_method_compareto_shared_ptr/) | ตรวจสอบว่ามีเมธอด CompareTo(SharedPtr<T>) อยู่ในชนิดที่ระบุหรือไม่ หากมี จะสืบทอด std::true_type มิฉะนั้นสืบทอด std::false_type สามารถใช้ใน std::enable_if |
| [IsEqualExist](./isequalexist/) | ตรวจสอบว่าชนิดให้การสนับสนุน operator == หรือไม่ |

## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| **bool** [IsOutOfBounds](./isoutofbounds/)(int, const Container\&) | ตรวจสอบว่าดัชนีอยู่นอกขอบเขตของคอนเทนเนอร์โดยไม่รวมขนาดของคอนเทนเนอร์ |
| **bool** [IsOutOfBounds](./isoutofbounds/)(std::int64_t, const Container\&) | ตรวจสอบว่าดัชนีอยู่นอกขอบเขตของคอนเทนเนอร์โดยไม่รวมขนาดของคอนเทนเนอร์ |
| **bool** [IsOutOfSize](./isoutofsize/)(int, const Container\&) | ตรวจสอบว่าดัชนีอยู่นอกขอบเขตของคอนเทนเนอร์รวมขนาดของคอนเทนเนอร์ด้วย |
| **bool** [IsOutOfSize](./isoutofsize/)(std::int64_t, const Container\&) | ตรวจสอบว่าดัชนีอยู่นอกขอบเขตของคอนเทนเนอร์รวมขนาดของคอนเทนเนอร์ด้วย |
| std::true_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(T *, T *) | ฟังก์ชันช่วยเหลือเพื่อกำหนดว่าคลาสเฉพาะมี operator == |
| std::false_type [HasOperatorEqualsHelper](./hasoperatorequalshelper/)(void *, void *) | ฟังก์ชันช่วยเหลือเพื่อกำหนดว่าคลาสเฉพาะมี operator == |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | พยายามดึงองค์ประกอบแรกของคอลเลกชัน |
| T [TryGetFirst](./trygetfirst/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, const [Func](../system/func/)\<T, **bool**\>\&, **bool**\&) | พยายามดึงองค์ประกอบแรกของคอลเลกชันที่ตรงตามฟังก์ชันเงื่อนไข |
| T [TryGetLast](./trygetlast/)([IEnumerable](../system.collections.generic/ienumerable/)\<T\>\&, **bool**\&) | พยายามดึงองค์ประกอบสุดท้ายของคอลเลกชัน |

## ประเภทนิยาม

| ชนิดนิยาม | คำอธิบาย |
| --- | --- |
| [has_operator_equals](./has_operator_equals/) | typedef จำลองเพื่อทดสอบการมีอยู่ของ operator == |