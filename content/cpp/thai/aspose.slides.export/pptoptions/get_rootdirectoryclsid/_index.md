---
title: get_RootDirectoryClsid()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึง GUID ของคลาสวัตถุ (CLSID) ที่เก็บไว้ในรายการไดเรกทอรีราก สามารถใช้เพื่อเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'
type: docs
weight: 1
url: /th/aspose.slides.export/pptoptions/get_rootdirectoryclsid/
---
## PptOptions::get_RootDirectoryClsid() เมธอด


แสดงถึง GUID ของคลาสวัตถุ (CLSID) ที่ถูกเก็บไว้ในรายการไดเรกทอรีราก. สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสารได้. ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'.

```cpp
System::Guid Aspose::Slides::Export::PptOptions::get_RootDirectoryClsid() override
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
* คลาส [PptOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)