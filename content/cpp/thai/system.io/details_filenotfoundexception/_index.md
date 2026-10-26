---
title: Details_FileNotFoundException
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "ข้อยกเว้นนี้จะถูกโยนเมื่อพยายามเข้าถึงไฟล์ที่ไม่มีอยู่บนดิสก์แล้วล้มเหลว. ห้ามสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง. ใช้คลาส FileNotFoundException แทน. ห้ามห่อหุ้มอินสแตนซ์ของคลาส FileNotFoundException เข้าไปใน System::SmartPtr."
type: docs
weight: 183
url: /th/system.io/details_filenotfoundexception/
---
## รายละเอียด Details_FileNotFoundException คลาส

ข้อยกเว้นที่ถูกโยนเมื่อการพยายามเข้าถึงไฟล์ที่ไม่มีอยู่บนดิสก์ล้มเหลว ไม่ควรสร้างอินสแตนซ์ของคลาสนี้ด้วยตนเอง ใช้คลาส FileNotFoundException แทน ไม่ควรห่อหุ้มอินสแตนซ์ของคลาส FileNotFoundException เข้าไปใน [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | รับชื่อไฟล์ที่ทำให้เกิดข้อยกเว้นนี้ |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## ดูเพิ่มเติม

* คลาส [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* เนมสเปซ [System::IO](../)
* ไลบรารี [Aspose.Slides](../../)