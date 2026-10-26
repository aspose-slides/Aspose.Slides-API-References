---
title: operator==()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เปรียบเทียบคู่คีย์-ค่าสองคู่โดยใช้หลักการ 'equals' semantics. ใช้ตัวดำเนินการ == หรือเมธอด EqualsTo สำหรับคีย์และค่า ไม่ว่าตัวใดจะถูกกำหนดไว้
type: docs
weight: 690
url: /th/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) ฟังก์ชัน

เปรียบเทียบคู่คีย์-ค่าสองคู่โดยใช้หลักการ 'equals' . ใช้ตัวดำเนินการ == หรือเมธอด EqualsTo สำหรับคีย์และค่า ทั้งสองค่า ไม่ว่าตัวใดจะถูกกำหนดไว้

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| TKey | ประเภทคีย์. |
| TValue | ประเภทค่า. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | ตัวดำเนินการฝั่งซ้าย. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | ตัวดำเนินการฝั่งขวา. |

### ค่าที่ส่งกลับ

คืนค่า true หากคีย์และค่าทั้งสองตรงกัน, false มิฉะนั้น.

## ดูเพิ่มเติม

* คลาส [KeyValuePair](../keyvaluepair/)
* เนมสเปซ [System::Collections::Generic](../)
* ไลบรารี [Aspose.Slides](../../)