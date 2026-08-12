---
title: SwapIfGreaterWithValues()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สลับคู่คีย์-ค่า หากเงื่อนไขการเปรียบเทียบเป็นจริง.
type: docs
weight: 53
url: /th/system.memoryextensions.details/swapifgreaterwithvalues/
---
## System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span\<TKey\>\&, Span\<TValue\>\&, std::function\<int32_t(const TKey\&, const TKey\&)>, int32_t, int32_t) ฟังก์ชัน

สลับคู่คีย์-ค่า หากเงื่อนไขการเปรียบเทียบเป็นจริง.

```cpp
template<typename TKey,typename TValue> void System::MemoryExtensions::Details::SwapIfGreaterWithValues(Span<TKey> &keys, Span<TValue> &values, std::function<int32_t(const TKey &, const TKey &)> comparer, int32_t i, int32_t j)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทของคีย์ |
| TValue | ประเภทของค่า |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| keys | [Span](../../system/span/)\<TKey\>\& | ช่วงของคีย์ |
| values | [Span](../../system/span/)\<TValue\>\& | ช่วงของค่า |
| comparer | std::function\<**int32_t**(const TKey\&, const TKey\&)> | [Comparison](../../system/comparison/) ฟังก์ชันสำหรับคีย์ |
| i | **int32_t** | ดัชนีแรกสำหรับเปรียบเทียบ |
| j | **int32_t** | ดัชนีที่สองสำหรับเปรียบเทียบ |

## ดูเพิ่มเติม

* คลาส [Span](../../system/span/)
* เนมสเปซ [System::MemoryExtensions::Details](../)
* ไลบรารี [Aspose.Slides](../../)