---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึง GUID ของคลาสอ็อบเจกต์ (CLSID) ที่ถูกเก็บไว้ในรายการไดเรกทอรีระดับราก สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'
type: docs
weight: 14
url: /th/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) เมธอด

แสดงถึง GUID ของคลาสอ็อบเจกต์ (CLSID) ที่ถูกเก็บไว้ในรายการไดเรกทอรีระดับราก สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'.

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
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