---
title: BlockCopy()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คัดลอกจำนวนไบต์ที่ระบุจากบัฟเฟอร์ต้นทางไปยังบัฟเฟอร์ปลายทาง.
type: docs
weight: 1
url: /th/system/buffer/blockcopy/
---
## Buffer::BlockCopy(const uint8_t *, int, uint8_t *, int, int) เมธอด

คัดลอกจำนวนไบต์ที่ระบุจากบัฟเฟอร์ต้นทางไปยังบัฟเฟอร์ปลายทาง.

```cpp
static void System::Buffer::BlockCopy(const uint8_t *src, int srcOffset, uint8_t *dst, int dstOffset, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const **uint8_t** * | ตัวชี้ไปยังบัฟเฟอร์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในบัฟเฟอร์ต้นทางที่เริ่มการคัดลอก |
| dst | **uint8_t** * | ตัวชี้ไปยังบัฟเฟอร์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในบัฟเฟอร์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | อาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | อาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const SharedPtr\<ArrayBase\>\&, int, const SharedPtr\<ArrayBase\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
static void System::Buffer::BlockCopy(const SharedPtr<ArrayBase> &src, int srcOffset, const SharedPtr<ArrayBase> &dst, int dstOffset, int count)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | อาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const [SharedPtr](../../sharedptr/)\<[ArrayBase](../../arraybase/)\>\& | อาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในมุมมองอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในมุมมองอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | มุมมองอาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในมุมมองอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const System::Details::ArrayView\<TDst\>\& | มุมมองอาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในมุมมองอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::ArrayView<TDst> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในมุมมองอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | อาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const System::Details::ArrayView\<TDst\>\& | มุมมองอาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในมุมมองอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const System::Details::ArrayView\<TSrc\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,typename TDst> static void System::Buffer::BlockCopy(const System::Details::ArrayView<TSrc> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในมุมมองอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::ArrayView\<TSrc\>\& | มุมมองอาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในมุมมองอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | อาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,std::size_t,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในสแตกอาเรย์ต้นทาง |
| NS | ขนาดของสแตกอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในสแตกอาเรย์ปลายทาง |
| ND | ขนาดของสแตกอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | สแตกอาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในสแตกอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const System::Details::StackArray\<TDst, ND\>\& | สแตกอาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในสแตกอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const SharedPtr\<Array\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,typename TDst,std::size_t> static void System::Buffer::BlockCopy(const SharedPtr<Array<TSrc>> &src, int srcOffset, const System::Details::StackArray<TDst, ND> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในสแตกอาเรย์ปลายทาง |
| ND | ขนาดของสแตกอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TSrc\>\>\& | อาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const System::Details::StackArray\<TDst, ND\>\& | สแตกอาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในสแตกอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## Buffer::BlockCopy(const System::Details::StackArray\<TSrc, NS\>\&, int, const SharedPtr\<Array\<TDst\>\>\&, int, int) เมธอด

แปลความหมายของสองอาเรย์ที่ระบุประเภทเป็นอาเรย์ดิบของไบต์และคัดลอกข้อมูลจากอาเรย์หนึ่งไปยังอีกรายการหนึ่ง.

```cpp
template<typename TSrc,std::size_t,typename TDst> static void System::Buffer::BlockCopy(const System::Details::StackArray<TSrc, NS> &src, int srcOffset, const SharedPtr<Array<TDst>> &dst, int dstOffset, int count)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| TSrc | ชนิดขององค์ประกอบในสแตกอาเรย์ต้นทาง |
| NS | ขนาดของสแตกอาเรย์ต้นทาง |
| TDst | ชนิดขององค์ประกอบในอาเรย์ปลายทาง |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| src | const System::Details::StackArray\<TSrc, NS\>\& | สแตกอาเรย์ต้นทาง |
| srcOffset | int | ออฟเซ็ตไบต์ในสแตกอาเรย์ต้นทางที่เริ่มการคัดลอก |
| dst | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<TDst\>\>\& | อาเรย์ปลายทาง |
| dstOffset | int | ออฟเซ็ตไบต์ในอาเรย์ปลายทางที่เริ่มแทรกข้อมูล |
| count | int | จำนวนไบต์ที่จะคัดลอก |

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../sharedptr/)
* คลาส [Buffer](../)
* คลาส [Array](../../array/)
* คลาส [ArrayBase](../../arraybase/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)