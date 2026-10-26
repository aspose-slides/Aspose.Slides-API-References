---
title: LastIndexOf()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดดัชนีของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุในช่วงของรายการของอาเรย์ที่กำหนดโดยตำแหน่งเริ่มต้นและจำนวนองค์ประกอบในช่วงนั้น
type: docs
weight: 703
url: /th/system/array/lastindexof/
---
## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int, int) เมธอด

กำหนดดัชนีของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุในช่วงของรายการของอาเรย์ที่กำหนดโดยตำแหน่งเริ่มต้นและจำนวนองค์ประกอบในช่วงนั้น

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &arr, const ValueType &value, int startIndex, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | ประเภทขององค์ประกอบในอาเรย์เป้าหมาย |
| ValueType | ประเภทของรายการที่จะค้นหาในอาเรย์ |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) เพื่อค้นหารายการที่ระบุใน |
| value | const [ValueType](../valuetype/)\& | ดัชนีของรายการที่ต้องกำหนด |
| startIndex | int | [Index](../../index/) ที่การค้นหาเริ่มต้น |
| count | int | จำนวนขององค์ประกอบในช่วงที่ต้องการค้นหา |

### Return Value

[Index](../../index/) ของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&, int) เมธอด

กำหนดดัชนีของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุในอาเรย์โดยเริ่มจากตำแหน่งที่ระบุ

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value, int startIndex)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | ประเภทขององค์ประกอบในอาเรย์เป้าหมาย |
| ValueType | ประเภทของรายการที่จะค้นหาในอาเรย์ |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) เพื่อค้นหารายการที่ระบุใน |
| value | const [ValueType](../valuetype/)\& | ดัชนีของรายการที่ต้องกำหนด |
| startIndex | int | [Index](../../index/) ที่การค้นหาเริ่มต้น |

### Return Value

[Index](../../index/) ของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## Array::LastIndexOf(const ArrayPtr\<ArrayType\>\&, const ValueType\&) เมธอด

กำหนดดัชนีของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุในอาเรย์

```cpp
template<typename ArrayType,typename ValueType> static int System::Array<T>::LastIndexOf(const ArrayPtr<ArrayType> &items, const ValueType &value)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| ArrayType | ประเภทขององค์ประกอบในอาเรย์เป้าหมาย |
| ValueType | ประเภทของรายการที่จะค้นหาในอาเรย์ |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| items | const [ArrayPtr](../../arrayptr/)\<ArrayType\>\& | [Array](../) เพื่อค้นหารายการที่ระบุใน |
| value | const [ValueType](../valuetype/)\& | ดัชนีของรายการที่ต้องกำหนด |

### Return Value

[Index](../../index/) ของการเกิดขึ้นครั้งสุดท้ายของรายการที่ระบุหากพบรายการ, มิฉะนั้น -1

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [ValueType](../valuetype/)
* Class [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)