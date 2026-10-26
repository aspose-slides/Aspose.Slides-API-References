---
title: get_RootDirectoryClsid()
second_title: Aspose.Slides C++ API 參考文件
description: 表示儲存在根目錄項目的物件類別 GUID (CLSID)。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，它對應於 'Microsoft Powerpoint.Slide.8'。
type: docs
weight: 1
url: /zh-hant/aspose.slides.export/ipptoptions/get_rootdirectoryclsid/
---
## IPptOptions::get_RootDirectoryClsid() 方法


表示儲存在根目錄項目的物件類別 GUID (CLSID)。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，它對應於 'Microsoft Powerpoint.Slide.8'。

```cpp
virtual System::Guid Aspose::Slides::Export::IPptOptions::get_RootDirectoryClsid()=0
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## 另見

* 類別 [Guid](../../../system/guid/)
* 類別 [IPptOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)