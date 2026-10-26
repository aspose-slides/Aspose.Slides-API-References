---
title: AreEqual()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบแอเรย์ของอ็อบเจกต์ที่ไม่เป็นพอยน์เตอร์.
type: docs
weight: 1
url: /th/system/testcompare/areequal/
---
## TestCompare::AreEqual(const SharedPtr\<Array\<T\>\>\&, const SharedPtr\<Array\<U\>\>\&) method

เปรียบเทียบแอเรย์ของอ็อบเจกต์ที่ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<T>> &arrA, const SharedPtr<Array<U>> &arrB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์แอเรย์แรก. |
| U | ชนิดของอิลีเมนต์แอเรย์ที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | อาเรย์ด้านซ้าย. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<U\>\>\& | อาเรย์ด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของแอเรย์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<Array\<SharedPtr\<T\>\>\>\&, const SharedPtr\<Array\<SharedPtr\<U\>\>\>\&) method

เปรียบเทียบแอเรย์ของพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<Array<SharedPtr<T>>> &arrA, const SharedPtr<Array<SharedPtr<U>>> &arrB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arrA | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | อาเรย์ด้านซ้าย. |
| arrB | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | อาเรย์ด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและอ็อบเจกต์ของแอเรย์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

เปรียบเทียบลิสต์ของอ็อบเจกต์ที่ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const SharedPtr<SCG::List<U>> &listB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์ลิสต์แรก. |
| U | ชนิดของอิลีเมนต์ลิสต์ที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | ลิสต์ด้านซ้าย. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | ลิสต์ด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของลิสต์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

เปรียบเทียบลิสต์ของพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &listA, const SharedPtr<SCG::List<SharedPtr<U>>> &listB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในลิสต์แรก. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในลิสต์ที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | ลิสต์ด้านซ้าย. |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | ลิสต์ด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและอ็อบเจกต์ของลิสต์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<T\>\>\&, const System::ArrayPtr\<U\>\&) method

เปรียบเทียบลิสต์กับแอเรย์ในกรณีที่อิลีเมนต์ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<T>> &listA, const System::ArrayPtr<U> &arrB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์ลิสต์. |
| U | [Array](../../array/) ชนิดของอิลีเมนต์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| listA | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<T\>\>\& | ลิสต์. |
| arrB | const [System::ArrayPtr](../../arrayptr/)\<U\>\& | [Array](../../array/). |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const System::ArrayPtr\<T\>\&, const SharedPtr\<SCG::List\<U\>\>\&) method

เปรียบเทียบลิสต์กับแอเรย์ในกรณีที่อิลีเมนต์ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<T> &arrA, const SharedPtr<SCG::List<U>> &listB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Array](../../array/) ชนิดของอิลีเมนต์. |
| U | ชนิดของอิลีเมนต์ลิสต์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arrA | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | [Array](../../array/). |
| listB | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<U\>\>\& | ลิสต์. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const System::ArrayPtr\<SharedPtr\<T\>\>\&, const SharedPtr\<SCG::List\<SharedPtr\<U\>\>\>\&) method

เปรียบเทียบลิสต์กับแอเรย์ในกรณีที่อิลีเมนต์เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::ArrayPtr<SharedPtr<T>> &arr, const SharedPtr<SCG::List<SharedPtr<U>>> &list)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | [Array](../../array/) ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในลิสต์. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | [Array](../../array/). |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | ลิสต์. |

### ค่าที่ส่งกลับ

true หากขนาดและอ็อบเจกต์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::List\<SharedPtr\<T\>\>\>\&, const System::ArrayPtr\<SharedPtr\<U\>\>\&) method

เปรียบเทียบลิสต์กับแอเรย์ในกรณีที่อิลีเมนต์เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::List<SharedPtr<T>>> &list, const System::ArrayPtr<SharedPtr<U>> &arr)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในลิสต์. |
| U | [Array](../../array/) ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| list | const [SharedPtr](../../sharedptr/)\<[SCG::List](../../../system.collections.generic/list/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | ลิสต์. |
| arr | const [System::ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | [Array](../../array/). |

### ค่าที่ส่งกลับ

true หากขนาดและอ็อบเจกต์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, U\>\>\&, const SharedPtr\<SCG::Dictionary\<K, U\>\>\&) method

เปรียบเทียบดิกชันนรีของชนิดที่แมพแบบไม่ใช่พอยน์เตอร์.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, U>> &dictA, const SharedPtr<SCG::Dictionary<K, U>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ชนิดของคีย์. |
| U | ชนิดของค่าที่แมพ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | ดิกชันนรีด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, U\>\>\& | ดิกชันนรีด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของดิกชันนรีตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::Dictionary\<K, SharedPtr\<U\>\>\>\&) method

เปรียบเทียบดิกชันนรีของชนิดที่แมพเป็นพอยน์เตอร์.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::Dictionary<K, SharedPtr<U>>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ชนิดของคีย์. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | ดิกชันนรีด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | ดิกชันนรีด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของดิกชันนรีตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::Dictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::Dictionary\<K2, U2\>\>\&) method

เปรียบเทียบดิกชันนรีของชนิดที่แตกต่างกัน.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Dictionary<K1, U1>> &dictA, const SharedPtr<SCG::Dictionary<K2, U2>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K1 | ชนิดของคีย์ดิกชันนรีด้านซ้าย. |
| U1 | ชนิดของค่าที่แมพในดิกชันนรีด้านซ้าย. |
| K2 | ชนิดของคีย์ดิกชันนรีด้านขวา. |
| U2 | ชนิดของค่าที่แมพในดิกชันนรีด้านขวา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K1, U1\>\>\& | ดิกชันนรีด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::Dictionary](../../../system.collections.generic/dictionary/)\<K2, U2\>\>\& | ดิกชันนรีด้านขวา. |

### ค่าที่ส่งกลับ

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<T\>\>\&, const SharedPtr\<SCG::HashSet\<U\>\>\&) method

เปรียบเทียบแฮชเซ็ตของอ็อบเจกต์ที่ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<T>> &containerPtrA, const SharedPtr<SCG::HashSet<U>> &containerPtrB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์แฮชเซ็ตแรก. |
| U | ชนิดของอิลีเมนต์แฮชเซ็ตที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| containerPtrA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<T\>\>\& | แฮชเซ็ตด้านซ้าย. |
| containerPtrB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<U\>\>\& | แฮชเซ็ตด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของแฮชเซ็ตตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::HashSet\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::HashSet\<SharedPtr\<U\>\>\>\&) method

เปรียบเทียบแฮชเซ็ตของพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::HashSet<SharedPtr<T>>> &contA, const SharedPtr<SCG::HashSet<SharedPtr<U>>> &contB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในแฮชเซ็ตแรก. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในแฮชเซ็ตที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| contA | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | แฮชเซ็ตด้านซ้าย. |
| contB | const [SharedPtr](../../sharedptr/)\<[SCG::HashSet](../../../system.collections.generic/hashset/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | แฮชเซ็ตด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของแฮชเซ็ตตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SCG::QueuePtr\<T\>\&, const SCG::QueuePtr\<U\>\&) method

เปรียบเทียบคิวของอ็อบเจกต์ที่ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<T> &queueA, const SCG::QueuePtr<U> &queueB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์คิวแรก. |
| U | ชนิดของอิลีเมนต์คิวที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<T\>\& | คิวด้านซ้าย. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<U\>\& | คิวด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของคิวตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SCG::QueuePtr\<SharedPtr\<T\>\>\&, const SCG::QueuePtr\<SharedPtr\<U\>\>\&) method

เปรียบเทียบคิวของพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SCG::QueuePtr<SharedPtr<T>> &queueA, const SCG::QueuePtr<SharedPtr<U>> &queueB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในคิวแรก. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในคิวที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| queueA | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<T\>\>\& | คิวด้านซ้าย. |
| queueB | const [SCG::QueuePtr](../../../system.collections.generic/queueptr/)\<[SharedPtr](../../sharedptr/)\<U\>\>\& | คิวด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของคิวตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<T\>\>\&, const SharedPtr\<SCG::Stack\<U\>\>\&) method

เปรียบเทียบสแต็กของอ็อบเจกต์ที่ไม่เป็นพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<T>> &stackA, const SharedPtr<SCG::Stack<U>> &stackB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอิลีเมนต์สแต็กแรก. |
| U | ชนิดของอิลีเมนต์สแต็กที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<T\>\>\& | สแต็กด้านซ้าย. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<U\>\>\& | สแต็กด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของสแต็กตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::Stack\<SharedPtr\<T\>\>\>\&, const SharedPtr\<SCG::Stack\<SharedPtr\<U\>\>\>\&) method

เปรียบเทียบสแต็กของพอยน์เตอร์.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::Stack<SharedPtr<T>>> &stackA, const SharedPtr<SCG::Stack<SharedPtr<U>>> &stackB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในสแต็กแรก. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้ในสแต็กที่สอง. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stackA | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<T\>\>\>\& | สแต็กด้านซ้าย. |
| stackB | const [SharedPtr](../../sharedptr/)\<[SCG::Stack](../../../system.collections.generic/stack/)\<[SharedPtr](../../sharedptr/)\<U\>\>\>\& | สแต็กด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของสแต็กตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, U\>\>\&) method

เปรียบเทียบดิกชันนรีที่จัดเรียงของชนิดที่แมพแบบไม่เป็นพอยน์เตอร์.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, U>> &dictA, const SharedPtr<SCG::SortedDictionary<K, U>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ชนิดของคีย์. |
| U | ชนิดของค่าที่แมพ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | ดิกชันนรีด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, U\>\>\& | ดิกชันนรีด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของดิกชันนรีตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K, SharedPtr\<U\>\>\>\&) method

เปรียบเทียบดิกชันนรีที่จัดเรียงของชนิดที่แมพเป็นพอยน์เตอร์.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedDictionary<K, SharedPtr<U>>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ชนิดของคีย์. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | ดิกชันนรีด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | ดิกชันนรีด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของดิกชันนรีตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedDictionary\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedDictionary\<K2, U2\>\>\&) method

เปรียบเทียบดิกชันนรีที่จัดเรียงของชนิดที่แตกต่างกัน.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedDictionary<K1, U1>> &dictA, const SharedPtr<SCG::SortedDictionary<K2, U2>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K1 | ชนิดของคีย์ดิกชันนรีด้านซ้าย. |
| U1 | ชนิดของค่าที่แมพในดิกชันนรีด้านซ้าย. |
| K2 | ชนิดของคีย์ดิกชันนรีด้านขวา. |
| U2 | ชนิดของค่าที่แมพในดิกชันนรีด้านขวา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K1, U1\>\>\& | ดิกชันนรีด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedDictionary](../../../system.collections.generic/sorteddictionary/)\<K2, U2\>\>\& | ดิกชันนรีด้านขวา. |

### ค่าที่ส่งกลับ

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, U\>\>\&, const SharedPtr\<SCG::SortedList\<K, U\>\>\&) method

เปรียบเทียบลิสต์ที่จัดเรียงของชนิดที่แมพแบบไม่เป็นพอยน์เตอร์.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, U>> &dictA, const SharedPtr<SCG::SortedList<K, U>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ชนิดของคีย์. |
| U | ชนิดของค่าที่แมพ. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | ลิสต์ด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, U\>\>\& | ลิสต์ด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของลิสต์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&, const SharedPtr\<SCG::SortedList\<K, SharedPtr\<U\>\>\>\&) method

เปรียบเทียบลิสต์ที่จัดเรียงของชนิดที่แมพเป็นพอยน์เตอร์.

```cpp
template<typename K,typename U> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictA, const SharedPtr<SCG::SortedList<K, SharedPtr<U>>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K | ชนิดของคีย์. |
| U | ชนิดของอ็อบเจกต์ที่พอยน์เตอร์ชี้. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | ลิสต์ด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K, [SharedPtr](../../sharedptr/)\<U\>\>\>\& | ลิสต์ด้านขวา. |

### ค่าที่ส่งกลับ

true หากขนาดและข้อมูลของลิสต์ตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const SharedPtr\<SCG::SortedList\<K1, U1\>\>\&, const SharedPtr\<SCG::SortedList\<K2, U2\>\>\&) method

เปรียบเทียบลิสต์ที่จัดเรียงของชนิดที่แตกต่างกัน.

```cpp
template<typename K1,typename U1,typename K2,typename U2> static bool System::TestCompare::AreEqual(const SharedPtr<SCG::SortedList<K1, U1>> &dictA, const SharedPtr<SCG::SortedList<K2, U2>> &dictB)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| K1 | ชนิดของคีย์ลิสต์ด้านซ้าย. |
| U1 | ชั้นของค่าที่แมพในลิสต์ด้านซ้าย. |
| K2 | ชนิดของคีย์ลิสต์ด้านขวา. |
| U2 | ชนิดของค่าที่แมพในลิสต์ด้านขวา. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| dictA | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K1, U1\>\>\& | ลิสต์ด้านซ้าย. |
| dictB | const [SharedPtr](../../sharedptr/)\<[SCG::SortedList](../../../system.collections.generic/sortedlist/)\<K2, U2\>\>\& | ลิสต์ด้านขวา. |

### ค่าที่ส่งกลับ

Always returns false as type conversion is forbidden here.

## TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr\&, const System::Collections::Specialized::StringCollectionPtr\&) method

เปรียบเทียบคอลเลกชันของสตริง.

```cpp
static bool System::TestCompare::AreEqual(const System::Collections::Specialized::StringCollectionPtr &arrA, const System::Collections::Specialized::StringCollectionPtr &arrB)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| arrA | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | คอลเลกชันด้านซ้าย. |
| arrB | const [System::Collections::Specialized::StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)\& | คอลเลกชันด้านขวา. |

### ค่าที่ส่งกลับ

True หากขนาดและข้อมูลตรงกัน, false มิฉะนั้น.

## TestCompare::AreEqual(const System::SharedPtr\<SCG::IEnumerable\<T\>\>\&, const System::SharedPtr\<SCG::IEnumerable\<U\>\>\&) method

เปรียบเทียบอินสแตนซ์ของ IEnumerable.

```cpp
template<typename T,typename U> static bool System::TestCompare::AreEqual(const System::SharedPtr<SCG::IEnumerable<T>> &et, const System::SharedPtr<SCG::IEnumerable<U>> &eu)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| et | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | อ็อบเจกต์ enumerable ด้านซ้าย. |
| eu | const [System::SharedPtr](../../sharedptr/)\<[SCG::IEnumerable](../../../system.collections.generic/ienumerable/)\<U\>\>\& | อ็อบเจกต์ enumerable ด้านขวา. |

### ค่าที่ส่งกลับ

True หากขนาดและข้อมูลตรงกัน, false มิฉะนั้น.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [Array](../../array/)
* Class [List](../../../system.collections.generic/list/)
* Class [Dictionary](../../../system.collections.generic/dictionary/)
* Class [HashSet](../../../system.collections.generic/hashset/)
* Class [QueuePtr](../../../system.collections.generic/queueptr/)
* Class [Stack](../../../system.collections.generic/stack/)
* Class [SortedDictionary](../../../system.collections.generic/sorteddictionary/)
* Class [SortedList](../../../system.collections.generic/sortedlist/)
* Class [StringCollectionPtr](../../../system.collections.specialized/stringcollectionptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [TestCompare](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)