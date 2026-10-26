---
title: "System::MemoryExtensions::Details"
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: 
type: docs
weight: 638
url: /th/system.memoryextensions.details/
---
## ฟังก์ชัน

| ฟังก์ชัน | รายละเอียด |
| --- | --- |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<U\>\&) | เปรียบเทียบสอง smart pointer |
| **int32_t** [Compare](./compare/)(const T\&, const T\&) | เปรียบเทียบค่าตัวเลขสองค่า |
| **int32_t** [Compare](./compare/)(const [SharedPtr](../system/sharedptr/)\<T\>\&, const U\&) | เปรียบเทียบ smart pointer กับค่า |
| **int32_t** [LastIndexOfImpl](./lastindexofimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**, const T\&) | ค้นหาดัชนีสุดท้ายของค่าหนึ่งใน span |
| **bool** [SequenceEqualImpl](./sequenceequalimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const **int32_t**, **int32_t**, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่า span สองอันเท่ากันหรือไม่โดยเริ่มจากตำแหน่งที่ระบุ |
| void [IntroSort](./introsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | การดำเนินการภายในของอัลกอริธึม introsort สำหรับคู่คีย์-ค่า |
| void [SwapIfGreaterWithValues](./swapifgreaterwithvalues/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>, **int32_t**, **int32_t**) | สลับคู่คีย์-ค่าหากเงื่อนไขการเปรียบเทียบเป็นจริง |
| void [InsertionSort](./insertionsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | ทำการ insertion sort บนคู่คีย์-ค่า |
| void [HeapSort](./heapsort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | ทำการ heap sort บนคู่คีย์-ค่า |
| void [Heapify](./heapify/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, **int32_t**, **int32_t**, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | รักษาคุณสมบัติ heap สำหรับคู่คีย์-ค่า |
| **int32_t** [PickPivotAndPartition](./pickpivotandpartition/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, std::function\<**int32_t**(const TKey\&, const TKey\&)>) | เลือก pivot และแบ่งพาร์ทิชันของคู่คีย์-ค่าเพื่อ quicksort |
| **int32_t** [BinarySearchImpl](./binarysearchimpl/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TValue\&, TCompareFunc) | การดำเนินการค้นหาแบบ binary search ทั่วไป |