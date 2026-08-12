---
title: Compare()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เปรียบเทียบวัตถุ Uri ที่ระบุโดยใช้กฎการเปรียบเทียบที่ระบุ
type: docs
weight: 521
url: /th/system/uri/compare/
---
## Uri::Compare(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&, UriComponents, UriFormat, StringComparison) เมธอด

เปรียบเทียบวัตถุ [Uri](../) ที่ระบุโดยใช้กฎการเปรียบเทียบที่ระบุ

```cpp
static int32_t System::Uri::Compare(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2, UriComponents partsToCompare, UriFormat compareFormat, StringComparison comparisonType)
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ตัวเปรียบเทียบตัวแรก |
| uri2 | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | ตัวเปรียบเทียบตัวที่สอง |
| partsToCompare | [UriComponents](../../uricomponents/) | ระบุส่วนของ **uri1** และ **uri2** ที่จะเปรียบเทียบ |
| compareFormat | [UriFormat](../../uriformat/) | ระบุการหนีอักขระที่ใช้เมื่อส่วนประกอบของ URI ถูกเปรียบเทียบ |
| comparisonType | [StringComparison](../../stringcomparison/) | หนึ่งในค่าของ StringComparison |

### ค่าที่ส่งคืน

ค่าติดลบหาก **uri1** น้อยกว่า **uri2**; 0 หาก uri1 และ uri2 เท่ากัน; ค่าบวกหาก **uri1** มากกว่า **uri2**

## ดูเพิ่มเติม

* Enum [UriComponents](../../uricomponents/)
* Enum [UriFormat](../../uriformat/)
* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Uri](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)