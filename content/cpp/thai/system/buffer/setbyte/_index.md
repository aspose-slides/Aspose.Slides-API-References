---
title: SetByte()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตีความอาร์เรย์ประเภทที่ระบุเป็นอาร์เรย์ไบต์ดิบและตั้งค่าค่าไบต์ที่ระบุที่ออฟเซ็ตไบต์ที่กำหนด
type: docs
weight: 40
url: /th/system/buffer/setbyte/
---
## Buffer::SetByte(const SharedPtr\<Array\<T\>\>\&, int, uint8_t) method

Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const SharedPtr<Array<T>> &array, int index, uint8_t value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | อาร์เรย์เป้าหมาย |
| index | int | ออฟเซ็ตเริ่มจากศูนย์ของไบต์ที่ต้องตั้งค่า |
| value | **uint8_t** | ค่าไบต์ที่จะตั้งค่า |

## Buffer::SetByte(const System::Details::ArrayView\<T\>\&, int, uint8_t) method

Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.

```cpp
template<typename T> static void System::Buffer::SetByte(const System::Details::ArrayView<T> &array, int index, uint8_t value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | มุมมองอาร์เรย์เป้าหมาย |
| index | int | ออฟเซ็ตเริ่มจากศูนย์ของไบต์ที่ต้องตั้งค่า |
| value | **uint8_t** | ค่าไบต์ที่จะตั้งค่า |

## Buffer::SetByte(const System::Details::StackArray\<T, N\>\&, int, uint8_t) method

Interprets the specified typed array as a raw byte array and sets the specified byte value at specified byte offset.

```cpp
template<typename T,std::size_t> static void System::Buffer::SetByte(const System::Details::StackArray<T, N> &array, int index, uint8_t value)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบในอาร์เรย์ |
| N | ขนาดของสแตกอาร์เรย์ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | สแตกอาร์เรย์เป้าหมาย |
| index | int | ออฟเซ็ตเริ่มจากศูนย์ของไบต์ที่ต้องตั้งค่า |
| value | **uint8_t** | ค่าไบต์ที่จะตั้งค่า |

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../../array/)
* Class [Buffer](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)