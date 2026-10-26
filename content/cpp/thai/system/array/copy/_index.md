---
title: Copy()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางไปยังอาร์เรย์ปลายทาง.
type: docs
weight: 729
url: /th/system/array/copy/
---
## Array::Copy(const ArrayPtr\<SrcType\>\&, const ArrayPtr\<DstType\>\&, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางไปยังอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::ArrayView\<SrcType\>, const ArrayPtr\<DstType\>\&, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากวิวอาร์เรย์ต้นทางไปยังอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | วิวอาร์เรย์ต้นทาง |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::ArrayView\<DstType\>, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางไปยังวิวอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| dstArray | System::Details::ArrayView\<DstType\> | วิวอาร์เรย์ปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากวิวอาร์เรย์ต้นทางไปยังวิวอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, System::Details::ArrayView<DstType> dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | วิวอาร์เรย์ต้นทาง |
| dstArray | System::Details::ArrayView\<DstType\> | วิวอาร์เรย์ปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, const ArrayPtr\<DstType\>\&, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์บนสแตกต้นทางไปยังอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, const ArrayPtr<DstType> &dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | อาร์เรย์บนสแตกต้นทาง |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(const ArrayPtr\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางไปยังอาร์เรย์บนสแน็คปลายทาง.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, System::Details::StackArray<DstType, N> &dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| dstArray | System::Details::StackArray\<DstType, N\>\& | อาร์เรย์บนสแตกปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์บนสแตกต้นทางไปยังอาร์เรย์บนสแตกปลายทาง.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, System::Details::StackArray<DstType, ND> &dstArray, int64_t count)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | อาร์เรย์บนสแตกต้นทาง |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | อาร์เรย์บนสแตกปลายทาง |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในอาร์เรย์ต้นทาง |
| DstType | ชนิดขององค์ประกอบในอาร์เรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากวิวอาร์เรย์ต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในวิวอาร์เรย์ต้นทาง |
| DstType | ชนิดขององค์ประกอบในอาร์เรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | วิวอาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในวิวอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในวิวอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในอาร์เรย์ต้นทาง |
| DstType | ชนิดขององค์ประกอบในวิวอาร์เรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | System::Details::ArrayView\<DstType\> | วิวอาร์เรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในวิวอาร์เรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::ArrayView\<SrcType\>, int64_t, System::Details::ArrayView\<DstType\>, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากวิวอาร์เรย์ต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในวิวอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,typename DstType> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> srcArray, int64_t srcIndex, System::Details::ArrayView<DstType> dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในวิวอาร์เรย์ต้นทาง |
| DstType | ชนิดขององค์ประกอบในวิวอาร์เรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\> | วิวอาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในวิวอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | System::Details::ArrayView\<DstType\> | วิวอาร์เรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในวิวอาร์เรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::StackArray\<SrcType, N\>\&, int64_t, const ArrayPtr\<DstType\>\&, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์บนสแตกต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในอาร์เรย์ปลายทาง.

```cpp
template<typename SrcType,std::size_t,typename DstType> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, N> &srcArray, int64_t srcIndex, const ArrayPtr<DstType> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในอาร์เรย์บนสแตกต้นทาง |
| DstType | ชนิดขององค์ประกอบในอาร์เรย์ปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, N\>\& | อาร์เรย์บนสไตก์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์บนสไตก์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | const [ArrayPtr](../../arrayptr/)\<DstType\>\& | อาร์เรย์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(const ArrayPtr\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, N\>\&, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์ต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในอาร์เรย์บนสแตกปลายทาง.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(const ArrayPtr<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, N> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในอาร์เรย์ต้นทาง |
| DstType | ชนิดขององค์ประกอบในอาร์เรย์บนสแตกปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | const [ArrayPtr](../../arrayptr/)\<SrcType\>\& | อาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | System::Details::StackArray\<DstType, N\>\& | อาร์เรย์บนสไตก์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์บนสไตก์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::StackArray\<SrcType, NS\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากอาร์เรย์บนสแตกต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในอาร์เรย์บนสแตกปลายทาง.

```cpp
template<typename SrcType,std::size_t,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::StackArray<SrcType, NS> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในอาร์เรย์บนสแตกต้นทาง |
| DstType | ชนิดขององค์ประกอบในอาร์เรย์บนสแตกปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::StackArray\<SrcType, NS\>\& | อาร์เรย์บนสไตก์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์บนสไตก์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | อาร์เรย์บนสไตก์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์บนสไตก์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## Array::Copy(System::Details::ArrayView\<SrcType\>\&, int64_t, System::Details::StackArray\<DstType, ND\>\&, int64_t, int64_t) เมธอด

คัดลอกจำนวนองค์ประกอบที่ระบุจากวิวอาร์เรย์ต้นทางที่ตำแหน่งเริ่มต้นที่ระบุไปยังตำแหน่งที่กำหนดในอาร์เรย์บนสแตกปลายทาง.

```cpp
template<typename SrcType,typename DstType,std::size_t> static void System::Array<T>::Copy(System::Details::ArrayView<SrcType> &srcArray, int64_t srcIndex, System::Details::StackArray<DstType, ND> &dstArray, int64_t dstIndex, int64_t count)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| SrcType | ชนิดขององค์ประกอบในวิวอาร์เรย์ต้นทาง |
| DstType | ชนิดขององค์ประกอบในอาร์เรย์บนสแตกปลายทาง |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| srcArray | System::Details::ArrayView\<SrcType\>\& | วิวอาร์เรย์ต้นทาง |
| srcIndex | **int64_t** | [Index](../../index/) ในวิวอาร์เรย์ต้นทางที่กำหนดจุดเริ่มต้นของช่วงรายการที่จะคัดลอก |
| dstArray | System::Details::StackArray\<DstType, ND\>\& | อาร์เรย์บนสไตก์ปลายทาง |
| dstIndex | **int64_t** | [Index](../../index/) ในอาร์เรย์บนสไตก์ปลายทางเพื่อเริ่มแทรกรายการที่คัดลอก |
| count | **int64_t** | จำนวนขององค์ประกอบที่ต้องคัดลอก |

## ดูเพิ่มเติม

* Typedef [ArrayPtr](../../arrayptr/)
* คลาส [Array](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)