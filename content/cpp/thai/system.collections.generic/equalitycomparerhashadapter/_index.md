---
title: EqualityComparerHashAdapter
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อะแดปเตอร์สำหรับใช้ IEqualityComparer ในการแฮช ใช้วัตถุตัวเปรียบเทียบ หากตั้งค่าไว้; หากไม่เช่นนั้น จะใช้วิธีแฮชที่มีอยู่ซึ่งเลือกโดยโครงสร้าง DictionaryHashSelector struct.
type: docs
weight: 677
url: /th/system.collections.generic/equalitycomparerhashadapter/
---
## EqualityComparerHashAdapter struct

อะแดปเตอร์สำหรับใช้ [IEqualityComparer](../iequalitycomparer/) ในการแฮช ใช้วัตถุตัวเปรียบเทียบ หากตั้งค่าไว้; หากไม่เช่นนั้น จะใช้วิธีแฮชที่มีอยู่ซึ่งเลือกโดยโครงสร้าง [DictionaryHashSelector](../dictionaryhashselector/) struct.

```cpp
template<typename T>class EqualityComparerHashAdapter
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| Hashed | type. |

## เมธอด

| Method | Description |
| --- | --- |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)() | สร้างอะแดปเตอร์ที่ไม่มีตัวเปรียบเทียบเพื่อใช้. |
|  [EqualityComparerHashAdapter](./equalitycomparerhashadapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | สร้างอะแดปเตอร์ด้วยตัวเปรียบเทียบที่กำหนดเพื่อใช้. |
| std::size_t [operator()](./operator_call/)(const T\&) const | คำนวณค่าแฮช. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | ตั้งค่าตัวเปรียบเทียบเพื่อใช้. |

## ดูเพิ่มเติม

* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)