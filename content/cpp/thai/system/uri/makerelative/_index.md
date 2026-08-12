---
title: MakeRelative()
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: กำหนดความแตกต่างระหว่างสองอินสแตนซ์ของ Uri.
type: docs
weight: 365
url: /th/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) เมธอด

กำหนดความแตกต่างระหว่างสองอินสแตนซ์ของ [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI ที่เปรียบเทียบกับ URI ปัจจุบัน |

### ค่าที่ส่งกลับ

หากชื่อโฮสต์และสกีมของ URI ที่แสดงโดยอ็อบเจกต์ปัจจุบันและ **toUri** เป็นค่าเดียวกัน เมธอดนี้จะคืนค่า [String](../../string/) ที่เป็น [Uri](../) เชิงสัมพันธ์ เมื่อต่อกับอินสแตนซ์ URI ปัจจุบัน จะได้ **toUri**. หากชื่อโฮสต์หรือสกีมต่างกัน เมธอดนี้จะคืนค่า [String](../../string/) ที่เป็นตัวแทนของพารามิเตอร์ **uri**.

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../sharedptr/)
* คลาส [String](../../string/)
* คลาส [Uri](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)