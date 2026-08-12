---
title: "System::Collections"
second_title: "อ้างอิง API Aspose.Slides สำหรับ C++"
description: 
type: docs
weight: 300
url: /th/system.collections/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) ของบิตที่สามารถเข้าถึงโดยดัชนี. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อขัดต่อการอ้างอิง. เสมอห่อคลาสนี้ในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [BitArrayPtr](./bitarrayptr/) | ตัวชี้ไปยัง [BitArray](./bitarray/). ประเภทนี้เป็นตัวชี้เพื่อจัดการการลบของอ็อบเจ็กต์อื่น. ควรจัดสรรบนสแตกและส่งต่อให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิงแบบ const. |
| [CollectionBase](./collectionbase/) | ให้คลาสฐานเชิงนามธรรมสำหรับคอลเลกชันที่กำหนดประเภทอย่างเข้มงวด. |
| [ICollection](./icollection/) | กำหนดอินเทอร์เฟซคอลเลกชันที่ไม่ใช่ generic. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) เป็นอินเทอร์เฟซฐานสำหรับคอลเลกชันที่ไม่เป็น generic ทั้งหมดที่สามารถทำการนับรายการได้. |
| [IEnumerator](./ienumerator/) | อินเทอร์เฟซของ enumerator ที่สามารถใช้เพื่อวนผ่านบางองค์ประกอบ. วัตถุของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะทำงานและ/หรือข้อขัดต่อการอ้างอิง. เสมอห่อคลาสนี้ในตัวชี้ [System::SmartPtr](../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | ตัวห่อที่สร้างการทำงานของ [IEnumerator](./ienumerator/) ที่ไม่เป็น generic บน Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) ที่เป็น generic - ตัวห่อสำหรับ Reference Types. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | ตัวห่อที่สร้างการทำงานของ [IEnumerator](./ienumerator/) ที่ไม่เป็น generic บน Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) ที่เป็น generic - ตัวห่อสำหรับ value Types. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) แสดงคอลเลกชันที่ไม่เป็น generic ของอ็อบเจ็กต์ที่สามารถเข้าถึงแยกกันโดยดัชนี. |
| [IListImplRefType](./ilistimplreftype/) | Stub ที่ทำการ implement อินเทอร์เฟซ [System::Collections::IList](./ilist/) บนวัตถุ [System::Collections::Generic::List](../system.collections.generic/list/) การทำงานสำหรับ reference types. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub ที่ทำการ implement อินเทอร์เฟซ [System::Collections::IList](./ilist/) บนวัตถุ [System::Collections::Generic::List](../system.collections.generic/list/) การทำงานสำหรับ value types. |
| [IListWrapper](./ilistwrapper/) | อินเทอร์เฟซเพื่อสนับสนุนการแคสท์จากคอลเลกชัน generic ไปยัง non-generic. |
| [Invalidatable](./invalidatable/) | คลาสที่ทำให้สามารถติดตามสถานะของลูกหลานผ่านอ็อบเจ็กต์ [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | คลาสที่ทำการ implement ตัวติดตามของอ็อบเจ็กต์ [Invalidatable](./invalidatable/). |