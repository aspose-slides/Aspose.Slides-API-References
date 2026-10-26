---
title: "System::MemoryExtensions"
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ให้เมธอดส่วนขยายสำหรับการดำเนินการหน่วยความจำบน span และ array
type: docs
weight: 625
url: /th/system.memoryextensions/
---
ให้เมธอดส่วนขยายสำหรับการทำงานกับหน่วยความจำบน span และอาร์เรย์

## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| [Span](../system/span/)\<T\> [AsSpan](./asspan/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, **int32_t**, **int32_t**) | สร้าง span จากอาร์เรย์ |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [AsSpan](./asspan/)(const [String](../system/string/)\&, **int32_t**, **int32_t**) | สร้าง read-only span จากสตริง |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const TComparable\&) | ทำการค้นหาแบบไบนารีบน span ที่เรียงลำดับ |
| **int32_t** [BinarySearch](./binarysearch/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | ทำการค้นหาแบบไบนารีบน span ที่เรียงลำดับโดยใช้ตัวเปรียบเทียบที่กำหนดเอง |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const TComparable\&) | ทำการค้นหาแบบไบนารีบน span ที่แก้ไขได้และเรียงลำดับ |
| **int32_t** [BinarySearch](./binarysearch/)(const [Span](../system/span/)\<T\>\&, const T\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | ทำการค้นหาแบบไบนารีบน span ที่แก้ไขได้และเรียงลำดับโดยใช้ตัวเปรียบเทียบที่กำหนดเอง |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | หาความยาวของคำนำร่วมระหว่างสอง span |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | หาความยาวของคำนำร่วมระหว่าง span ที่แก้ไขได้และ span ที่อ่านได้เท่านั้น |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | หาความยาวของคำนำร่วมระหว่างสอง span ที่แก้ไขได้ |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | หาความยาวของคำนำร่วมระหว่างสอง span โดยใช้ตัวเปรียบเทียบความเท่าเทียมที่กำหนดเอง |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | หาความยาวของคำนำร่วมระหว่าง span ที่แก้ไขได้และ span ที่อ่านได้เท่านั้นโดยใช้ตัวเปรียบเทียบความเท่าเทียมที่กำหนดเอง |
| **int32_t** [CommonPrefixLength](./commonprefixlength/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TEqualityComparer\>\&) | หาความยาวของคำนำร่วมระหว่างสอง span ที่แก้ไขได้โดยใช้ตัวเปรียบเทียบความเท่าเทียมที่กำหนดเอง |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ตรวจสอบว่า read-only span มีค่าที่ระบุหรือไม่ |
| **bool** [Contains](./contains/)(const [Span](../system/span/)\<T\>\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีค่าที่ระบุหรือไม่ |
| **bool** [Contains](./contains/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | ตรวจสอบว่า span ตัวอักษรมี span ตัวอักษรอื่นที่ตรงตามกฎการเปรียบเทียบที่กำหนดหรือไม่ |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า read-only span มีค่าใดค่าหนึ่งจากสองค่าหรือไม่ |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ตรวจสอบว่า read-only span มีค่าใดค่าหนึ่งจากสามค่าหรือไม่ |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีค่าใดค่าหนึ่งจากสองค่าหรือไม่ |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีค่าใดค่าหนึ่งจากสามค่าหรือไม่ |
| **bool** [ContainsAny](./containsany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่า read-only span มีค่าที่มาจาก span อื่นหรือไม่ |
| **bool** [ContainsAny](./containsany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่า span ที่แก้ไขได้มีค่าที่มาจาก read-only span หรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ตรวจสอบว่า read-only span มีองค์ประกอบใดนอกจากสามค่าที่ระบุหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีองค์ประกอบใดนอกจากสามค่าที่ระบุหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า read-only span มีองค์ประกอบใดนอกจากสองค่าที่ระบุหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีองค์ประกอบใดนอกจากสองค่าที่ระบุหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ตรวจสอบว่า read-only span มีองค์ประกอบใดนอกจากค่าที่ระบุหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีองค์ประกอบใดนอกจากค่าที่ระบุหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่า read-only span มีองค์ประกอบใดนอกจากที่อยู่ใน span อื่นหรือไม่ |
| **bool** [ContainsAnyExcept](./containsanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่า span ที่แก้ไขได้มีองค์ประกอบใดนอกจากที่อยู่ใน read-only span หรือไม่ |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า read-only span มีองค์ประกอบใดที่อยู่นอกช่วงที่ระบุหรือไม่ |
| **bool** [ContainsAnyExceptInRange](./containsanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีองค์ประกอบใดที่อยู่นอกช่วงที่ระบุหรือไม่ |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า read-only span มีองค์ประกอบใดที่อยู่ในช่วงที่ระบุหรือไม่ |
| **bool** [ContainsAnyInRange](./containsanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ตรวจสอบว่า span ที่แก้ไขได้มีองค์ประกอบใดที่อยู่ในช่วงที่ระบุหรือไม่ |
| void [CopyTo](./copyto/)(const [ArrayPtr](../system/arrayptr/)\<T\>\&, [Span](../system/span/)\<T\>\&) | คัดลอกองค์ประกอบจากอาร์เรย์ไปยัง span |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | นับจำนวนการพบค่าหนึ่งใน read-only span |
| **int32_t** [Count](./count/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | นับจำนวนการพบ span ภายใน read-only span อื่น |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const T\&) | นับจำนวนการพบค่าหนึ่งใน Span<T> |
| **int32_t** [Count](./count/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | นับจำนวนการพบ ReadOnlySpan<T> ใน Span<T> |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | กำหนดว่า ReadOnlySpan<T> สิ้นสุดด้วยค่าหนึ่งหรือไม่ |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | กำหนดว่า ReadOnlySpan<T> สิ้นสุดด้วย ReadOnlySpan<T> อื่นหรือไม่ |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | กำหนดว่า Span<T> สิ้นสุดด้วย ReadOnlySpan<T> หรือไม่ |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | กำหนดว่า ReadOnlySpan<T> สิ้นสุดด้วย Span<T> หรือไม่ |
| **bool** [EndsWith](./endswith/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | กำหนดว่า Span<T> สิ้นสุดด้วย Span<T> อื่นหรือไม่ |
| **bool** [EndsWith](./endswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | กำหนดว่า ReadOnlySpan<char16_t> สิ้นสุดด้วยค่าที่ระบุโดยใช้ StringComparison |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งของค่า ReadOnlySpan<T> ใน ReadOnlySpan<T> อื่น |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ค้นหาตำแหน่งของค่าหนึ่งใน ReadOnlySpan<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งของค่า ReadOnlySpan<T> ใน Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | ค้นหาตำแหน่งของค่าหนึ่งใน Span<T> |
| **int32_t** [IndexOf](./indexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | ค้นหาตำแหน่งของค่า ReadOnlySpan<char16_t> ใน ReadOnlySpan<char16_t> ด้วย StringComparison |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งของการเกิดครั้งแรกของค่าใดค่าหนึ่งจากสองค่าที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาตำแหน่งของการเกิดครั้งแรกของค่าใดค่าหนึ่งจากสามค่าที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งของการเกิดครั้งแรกของค่าใดค่าหนึ่งจากสองค่าที่ระบุใน Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาตำแหน่งของการเกิดครั้งแรกของค่าใดค่าหนึ่งจากสามค่าที่ระบุใน Span<T> |
| **int32_t** [IndexOfAny](./indexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งของค่าที่มาจาก span ใดค่าหนึ่งใน ReadOnlySpan<T> อื่น |
| **int32_t** [IndexOfAny](./indexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งของค่าที่มาจาก span ใดค่าหนึ่งใน Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าใดค่าหนึ่งจากสองค่าที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าใดค่าหนึ่งจากสามค่าที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าที่ระบุใน Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าใดค่าหนึ่งจากสองค่าที่ระบุใน Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าใดค่าหนึ่งจากสามค่าที่ระบุใน Span<T> |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าใดค่าหนึ่งใน span ของค่า |
| **int32_t** [IndexOfAnyExcept](./indexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่ไม่เท่ากับค่าใดค่าหนึ่งใน span ของค่าใน Span<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่อยู่นอกช่วงที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyExceptInRange](./indexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่อยู่นอกช่วงที่ระบุใน Span<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่อยู่ในช่วงที่ระบุใน ReadOnlySpan<T> |
| **int32_t** [IndexOfAnyInRange](./indexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งขององค์ประกอบแรกที่อยู่ในช่วงที่ระบุใน Span<T> |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาการเกิดครั้งสุดท้ายของลำดับภายใน span |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าหนึ่งภายใน span |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาการเกิดครั้งสุดท้ายของลำดับภายใน span ที่แก้ไขได้ |
| **int32_t** [LastIndexOf](./lastindexof/)(const [Span](../system/span/)\<T\>\&, const T\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าหนึ่งภายใน span ที่แก้ไขได้ |
| **int32_t** [LastIndexOf](./lastindexof/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | ค้นหาการเกิดครั้งสุดท้ายของค่าภายใน span โดยใช้การเปรียบเทียบสตริงที่ระบุ |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าใดค่าหนึ่งจากสามค่าที่ระบุภายใน span |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าใดค่าหนึ่งจากสามค่าที่ระบุภายใน span ที่แก้ไขได้ |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าใดค่าหนึ่งจากสองค่าที่ระบุภายใน span |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าใดค่าหนึ่งจากสองค่าที่ระบุภายใน span ที่แก้ไขได้ |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าที่มาจากลำดับใดค่าหนึ่งภายใน span |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าที่มาจากลำดับใดค่าหนึ่งภายใน span ที่แก้ไขได้ |
| **int32_t** [LastIndexOfAny](./lastindexofany/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | ค้นหาการเกิดครั้งสุดท้ายของค่าที่มาจากลำดับที่แก้ไขได้ภายใน span ที่แก้ไขได้ |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าที่ระบุสามค่าในช่วง. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าที่ระบุสามค่าในช่วงที่เปลี่ยนแปลงได้. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าที่ระบุสองค่าในช่วง. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าที่ระบุสองค่าในช่วงที่เปลี่ยนแปลงได้. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าที่ระบุหนึ่งค่าในช่วง. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าที่ระบุหนึ่งค่าในช่วงที่เปลี่ยนแปลงได้. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าจากลำดับในช่วง. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าจากลำดับในช่วงที่เปลี่ยนแปลงได้. |
| **int32_t** [LastIndexOfAnyExcept](./lastindexofanyexcept/)(const [Span](../system/span/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ยกเว้นค่าจากลำดับที่เปลี่ยนแปลงได้ในช่วงที่เปลี่ยนแปลงได้. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ที่อยู่นอกช่วงที่ระบุในช่วง. |
| **int32_t** [LastIndexOfAnyExceptInRange](./lastindexofanyexceptinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ที่อยู่นอกช่วงที่ระบุในช่วงที่เปลี่ยนแปลงได้. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ที่อยู่ในช่วงที่ระบุในช่วง. |
| **int32_t** [LastIndexOfAnyInRange](./lastindexofanyinrange/)(const [Span](../system/span/)\<T\>\&, const T\&, const T\&) | ค้นหาตำแหน่งล่าสุดขององค์ประกอบใด ๆ ที่อยู่ในช่วงที่ระบุในช่วงที่เปลี่ยนแปลงได้. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | กำหนดว่ามี ReadOnlySpans สองตัวทับซ้อนกันในหน่วยความจำโดยไม่คำนวณออฟเซ็ต. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | กำหนดว่ามี [Span](../system/span/) และ [ReadOnlySpan](../system/readonlyspan/) ทับซ้อนกันในหน่วยความจำโดยไม่คำนวณออฟเซ็ต. |
| **bool** [Overlaps](./overlaps/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | กำหนดว่ามี ReadOnlySpans สองตัวทับซ้อนกันในหน่วยความจำและคำนวณออฟเซ็ต. |
| **bool** [Overlaps](./overlaps/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, **int32_t**\&) | กำหนดว่ามี [Span](../system/span/) และ [ReadOnlySpan](../system/readonlyspan/) ทับซ้อนกันในหน่วยความจำและคำนวณออฟเซ็ต. |
| void [Replace](./replace/)([Span](../system/span/)\<T\>\&, const T\&, const T\&) | แทนที่ค่าทั้งหมดด้วยค่าตัวใหม่ใน [Span](../system/span/). |
| void [Replace](./replace/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [Span](../system/span/)\<T\>\&, const T\&, const T\&) | คัดลอกองค์ประกอบจากแหล่งที่มาสู่ปลายทางโดยแทนค่าที่ระบุระหว่างการคัดลอก. |
| void [Reverse](./reverse/)([Span](../system/span/)\<T\>\&) | กลับลำดับขององค์ประกอบใน [Span](../system/span/) โดยทำในที่เดียว. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | เปรียบเทียบ ReadOnlySpans สองตัวตามลำดับอักขระ. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | เปรียบเทียบ [Span](../system/span/) และ [ReadOnlySpan](../system/readonlyspan/) ตามลำดับอักขระ. |
| **int32_t** [SequenceCompareTo](./sequencecompareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | เปรียบเทียบ [ReadOnlySpan](../system/readonlyspan/) และ [Span](../system/span/) ตามลำดับอักขระ. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | กำหนดว่ามี ReadOnlySpans สองตัวมีองค์ประกอบเดียวกันในลำดับเดียวกันหรือไม่. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | กำหนดว่ามี [Span](../system/span/) และ [ReadOnlySpan](../system/readonlyspan/) มีองค์ประกอบเดียวกันในลำดับเดียวกันหรือไม่. |
| **bool** [SequenceEqual](./sequenceequal/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | กำหนดว่ามี ReadOnlySpans สองตัวมีองค์ประกอบเท่ากันโดยใช้ตัวเปรียบเทียบที่กำหนดเอง. |
| **bool** [SequenceEqual](./sequenceequal/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | กำหนดว่ามี [Span](../system/span/) และ [ReadOnlySpan](../system/readonlyspan/) มีองค์ประกอบเท่ากันโดยใช้ตัวเปรียบเทียบที่กำหนดเอง. |
| void [Sort](./sort/)(const [Span](../system/span/)\<T\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | เรียงลำดับ [Span](../system/span/) โดยใช้ตัวเปรียบเทียบที่กำหนดเอง. |
| void [Sort](./sort/)([Span](../system/span/)\<T\>\&) | เรียงลำดับ [Span](../system/span/) โดยใช้การเปรียบเทียบเริ่มต้น. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, const [SharedPtr](../system/sharedptr/)\<TComparer\>\&) | เรียงลำดับคู่คีย์-ค่าโดยใช้ตัวเปรียบเทียบที่กำหนดเอง (คีย์และค่าถูกจัดเรียงร่วมกัน) |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&, [System::Comparison](../system/comparison/)\<TKey\>) | เรียงลำดับคู่คีย์-ค่าโดยใช้ตัวแทนการเปรียบเทียบ. |
| void [Sort](./sort/)([Span](../system/span/)\<TKey\>\&, [Span](../system/span/)\<TValue\>\&) | เรียงลำดับคู่คีย์-ค่าโดยใช้การเปรียบเทียบเริ่มต้น. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ตรวจสอบว่าช่วงเริ่มต้นด้วยค่านั้นหรือไม่. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่าช่วงเริ่มต้นด้วยช่วงค่าที่ระบุหรือไม่. |
| **bool** [StartsWith](./startswith/)(const [Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตรวจสอบว่าช่วงที่เปลี่ยนแปลงได้เริ่มต้นด้วยช่วงค่าที่อ่านอย่างเดียวที่ระบุหรือไม่. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [Span](../system/span/)\<T\>\&) | ตรวจสอบว่าช่วงที่อ่านอย่างเดียวเริ่มต้นด้วยช่วงค่าที่เปลี่ยนแปลงได้ที่ระบุหรือไม่. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | ตรวจสอบว่าช่วงอักขระเริ่มต้นด้วยช่วงค่าที่ระบุโดยใช้ StringComparison. |
| **bool** [StartsWith](./startswith/)(const [ReadOnlySpan](../system/readonlyspan/)\<[String](../system/string/)\>\&, const char16_t *) | ตรวจสอบว่าช่วงสตริงเริ่มต้นด้วยอาเรย์อักขระที่ระบุหรือไม่. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, T) | ตัดองค์ประกอบที่ระบุออกจากทั้งสองด้านของช่วงที่กำหนดประเภท. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, T) | ตัดองค์ประกอบที่ระบุออกจากทั้งสองด้านของช่วงที่กำหนดประเภทที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตัดองค์ประกอบที่ระบุออกจากทั้งสองด้านของช่วงที่กำหนดประเภท. |
| [Span](../system/span/)\<T\> [Trim](./trim/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตัดองค์ประกอบที่ระบุออกจากทั้งสองด้านของช่วงที่กำหนดประเภทที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [Trim](./trim/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระช่องว่างออกจากทั้งสองด้านของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [Trim](./trim/)([Span](../system/span/)\<char16_t\>\&) | ตัดอักขระช่องว่างออกจากทั้งสองด้านของช่วงอักขระที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ตัดองค์ประกอบที่ระบุออกจากด้านปลายของช่วงที่กำหนดประเภท. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const T\&) | ตัดองค์ประกอบที่ระบุออกจากด้านปลายของช่วงที่กำหนดประเภทที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตัดองค์ประกอบที่ระบุออกจากด้านปลายของช่วงที่กำหนดประเภท. |
| [Span](../system/span/)\<T\> [TrimEnd](./trimend/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตัดองค์ประกอบที่ระบุออกจากด้านปลายของช่วงที่กำหนดประเภทที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระช่องว่างออกจากด้านปลายของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&) | ตัดอักขระช่องว่างออกจากด้านปลายของช่วงอักขระที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | ตัดอักขระที่ระบุออกจากด้านปลายของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, char16_t) | ตัดอักขระที่ระบุออกจากด้านปลายของช่วงอักขระที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimEnd](./trimend/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระที่ระบุหลายตัวออกจากด้านปลายของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [TrimEnd](./trimend/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระที่ระบุหลายตัวออกจากด้านปลายของช่วงอักขระที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const T\&) | ตัดองค์ประกอบที่ระบุออกจากด้านเริ่มของช่วงที่กำหนดประเภท. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const T\&) | ตัดองค์ประกอบที่ระบุออกจากด้านเริ่มของช่วงที่กำหนดประเภทที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<T\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตัดองค์ประกอบที่ระบุออกจากด้านเริ่มของช่วงที่กำหนดประเภท. |
| [Span](../system/span/)\<T\> [TrimStart](./trimstart/)([Span](../system/span/)\<T\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<T\>\&) | ตัดองค์ประกอบที่ระบุออกจากด้านเริ่มของช่วงที่กำหนดประเภทที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระช่องว่างออกจากด้านเริ่มของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&) | ตัดอักขระช่องว่างออกจากด้านเริ่มของช่วงอักขระที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, char16_t) | ตัดอักขระที่ระบุออกจากด้านเริ่มของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, char16_t) | ตัดอักขระที่ระบุออกจากด้านเริ่มของช่วงอักขระที่เปลี่ยนแปลงได้. |
| [ReadOnlySpan](../system/readonlyspan/)\<char16_t\> [TrimStart](./trimstart/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระที่ระบุหลายตัวออกจากด้านเริ่มของช่วงอักขระ. |
| [Span](../system/span/)\<char16_t\> [TrimStart](./trimstart/)([Span](../system/span/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตัดอักขระที่ระบุหลายตัวออกจากด้านเริ่มของช่วงอักขระที่เปลี่ยนแปลงได้. |
| **int32_t** [CompareTo](./compareto/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | เปรียบเทียบช่วงอักขระสองช่วงตามกฎการเปรียบเทียบสตริงที่ระบุ. |
| **bool** [Equals](./equals/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [StringComparison](../system/stringcomparison/)) | เปรียบเทียบ ReadOnlySpan<char16_t> สองตัวเพื่อความเท่ากันโดยใช้ StringComparison. |
| **bool** [IsWhiteSpace](./iswhitespace/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&) | ตรวจสอบว่าช่วงทั้งหมดประกอบด้วยอักขระช่องว่างเท่านั้นหรือไม่. |
| **int32_t** [ToLower](./tolower/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | แปลงอักขระเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่ระบุ. |
| **int32_t** [ToLowerInvariant](./tolowerinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | แปลงอักขระเป็นตัวพิมพ์เล็กโดยใช้วัฒนธรรมที่คงที่. |
| **int32_t** [ToUpper](./toupper/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&, const [SharedPtr](../system/sharedptr/)\<[Globalization::CultureInfo](../system.globalization/cultureinfo/)\>\&) | แปลงอักขระเป็นตัวพิมพ์ใหญ่โดยใช้วัฒนธรรมที่ระบุ. |
| **int32_t** [ToUpperInvariant](./toupperinvariant/)(const [ReadOnlySpan](../system/readonlyspan/)\<char16_t\>\&, [Span](../system/span/)\<char16_t\>\&) | แปลงอักขระเป็นตัวพิมพ์ใหญ่โดยใช้วัฒนธรรมที่คงที่. |