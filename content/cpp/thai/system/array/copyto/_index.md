---
title: CopyTo()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: คัดลอกทุกองค์ประกอบของอาเรย์ปัจจุบันไปยังอาเรย์ปลายทางที่ระบุ โดยองค์ประกอบจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ arrayIndex
type: docs
weight: 118
url: /th/system/array/copyto/
---
## Array::CopyTo(ArrayPtr\<T\>, int) เมธอด

คัดลอกทุกองค์ประกอบของอาเรย์ปัจจุบันไปยังอาเรย์ปลายทางที่ระบุ ตัวองค์ประกอบจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ arrayIndex

```cpp
virtual void System::Array<T>::CopyTo(ArrayPtr<T> arr, int arrayIndex) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | อาเรย์ปลายทาง |
| arrayIndex | int | [Index](../../index/) ในอาเรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t) const เมธอด

คัดลอกทุกองค์ประกอบของอาเรย์ปัจจุบันไปยังอาเรย์ปลายทางที่ระบุ ตัวองค์ประกอบจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t dstIndex) const
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| DstType | ประเภทขององค์ประกอบในอาเรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาเรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาเรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t) const เมธอด

คัดลอกทุกองค์ประกอบของอาเรย์ปัจจุบันไปยังวิวอาเรย์ปลายทางที่ระบุ ตัวองค์ประกอบจะถูกแทรกลงในวิวอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t dstIndex) const
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| DstType | ประเภทขององค์ประกอบในวิวอาเรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | วิวอาเรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในวิวอาเรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |

## Array::CopyTo(const ArrayPtr\<DstType\>\&, int64_t, int64_t, int64_t) const เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาเรย์ปัจจุบันเริ่มจากตำแหน่งที่ระบุไปยังอาเรย์ปลายทางที่ระบุ ตัวองค์ประกอบจะถูกแทรกลงในอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const ArrayPtr<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| DstType | ประเภทขององค์ประกอบในอาเรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาเรย์ปลายทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาเรย์ต้นทางเพื่อเริ่มคัดลอกรายการ |
| dstIndex | **int64_t** | [Index](../../index/) ในอาเรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่จะคัดลอก |

## Array::CopyTo(const System::Details::ArrayView\<DstType\>\&, int64_t, int64_t, int64_t) const เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาเรย์ปัจจุบันเริ่มจากตำแหน่งที่ระบุไปยังวิวอาเรย์ปลายทางที่ระบุ ตัวองค์ประกอบจะถูกแทรกลงในวิวอาเรย์ปลายทางเริ่มจากดัชนีที่ระบุโดยอาร์กิวเมนต์ dstIndex

```cpp
template<typename DstType> void System::Array<T>::CopyTo(const System::Details::ArrayView<DstType> &dstArray, int64_t srcIndex, int64_t dstIndex, int64_t count) const
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| DstType | ประเภทขององค์ประกอบในวิวอาเรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| dstArray | const System::Details::ArrayView\<DstType\>\& | วิวอาเรย์ปลายทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาเรย์ต้นทางเพื่อเริ่มคัดลอกรายการ |
| dstIndex | **int64_t** | [Index](../../index/) ในวิวอาเรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่จะคัดลอก |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* Library [Aspose.Slides](../../../)