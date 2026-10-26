---
title: get_RootDirectoryClsid()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึง GUID ของคลาสอ็อบเจ็กต์ (CLSID) ที่จัดเก็บในรายการไดเรกทอรีราก. สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร. ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'.
type: docs
weight: 1
url: /th/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() เมธอด


แสดงถึง GUID ของคลาสอ็อบเจ็กต์ (CLSID) ที่จัดเก็บในรายการไดเรกทอรีราก. สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร. ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'.

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## ดูเพิ่มเติม

* คลาส [Guid](../../../system/guid/)
* คลาส [IPptOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)