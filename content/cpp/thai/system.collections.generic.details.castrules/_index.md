---
title: "System::Collections::Generic::Details::CastRules"
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 365
url: /th/system.collections.generic.details.castrules/
---
## โครงสร้าง

| โครงสร้าง | คำอธิบาย |
| --- | --- |
| [CastType](./casttype/) | มีฟังก์ชันเพื่อกำหนดประเภทการแคสต์ |
## ฟังก์ชัน

| ฟังก์ชัน | คำอธิบาย |
| --- | --- |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทแหล่งและผลลัพธ์เป็นประเภทเดียวกัน |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทแหล่งสามารถแคสต์แบบสถิตย์เป็นประเภทผลลัพธ์ได้ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทต่างกันและประเภทแหล่งไม่สามารถแคสต์แบบสถิตย์เป็นประเภทผลลัพธ์ได้ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทแหล่งถูกบ็อกซ์เป็นอินสแตนซ์ของคลาส [Nullable](../system/nullable/) |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทแหล่งถูกแอนบ็อกซ์จากอินสแตนซ์ของคลาส [Nullable](../system/nullable/) |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทแหล่งถูกบ็อกซ์เป็นอินสแตนซ์ของคลาส [Object](../system/object/) |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อประเภทแหล่งถูกแอนบ็อกซ์จากอินสแตนซ์ของคลาส [Object](../system/object/) |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, Result\> [Cast](./cast/)(Source) | แปลงประเภทแหล่งให้เป็นประเภทผลลัพธ์ ใช้เมื่อการแคสต์ไม่ถูกต้องหรือการแปลงเป็นแบบชัดเจน |
| **bool** [IsNull](./isnull/)(T) | ตรวจสอบว่าค่าที่แสดงเป็น nullptr |
| **bool** [IsNull](./isnull/)([SharedPtr](../system/sharedptr/)\<T\>) | ตรวจสอบว่าค่าที่แสดงเป็น nullptr |
| **bool** [IsNull](./isnull/)([Nullable](../system/nullable/)\<T\>) | ตรวจสอบว่าค่าที่แสดงเป็น nullptr |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::None, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Static, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Dynamic, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableBoxing, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::NullableUnboxing, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Boxing, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Unboxing, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |
| std::enable_if_t\<[CastType](./casttype/)\<Source, Result\>::Invalid, **bool**\> [CanCast](./cancast/)(Source) | ตรวจสอบความเป็นไปได้ของการแคสต์ |