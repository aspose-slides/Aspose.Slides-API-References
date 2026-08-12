---
title: PeekChar()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: อ่านอักขระเดี่ยวหนึ่งตัวจากสตรีมอินพุตโดยไม่เปลี่ยนตำแหน่งตัวชี้การอ่านของสตรีม
type: docs
weight: 53
url: /th/system.io/binaryreader/peekchar/
---
## BinaryReader::PeekChar() เมธอด

อ่านอักขระเดียวจากสตรีมอินพุตโดยไม่เปลี่ยนตำแหน่งตัวชี้การอ่านของสตรีม

```cpp
virtual int System::IO::BinaryReader::PeekChar()
```

### ค่าที่คืน

อักขระที่อ่านได้ถูกเข้ารหัสด้วย UTF-16; หากอักขระที่อ่านได้ถูกแทนด้วยสองโค้ดพอยท์ในการเข้ารหัส UTF-16 จะคืนค่าเฉพาะส่วนสูงของ surrogate; หากไม่มีอักขระใดถูกอ่าน จะคืนค่า -1

## ดูเพิ่มเติม

* คลาส [BinaryReader](../)
* เนมสเปซ [System::IO](../../)
* ไลบรารี [Aspose.Slides](../../../)