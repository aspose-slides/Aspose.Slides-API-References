---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API 參考文件
description: 代表儲存在根目錄項目中的物件類別 GUID（CLSID）。可用於文件應用程式的 COM 啟動。預設值為 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。
type: docs
weight: 14
url: /zh-hant/aspose.slides.export/ipptoptions/set_rootdirectoryclsid/
---
## IPptOptions::set_RootDirectoryClsid(System::Guid) 方法

表示儲存在根目錄項目中的物件類別 GUID（CLSID）。可用於文件應用程式的 COM 啟動。預設值是 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，對應於 'Microsoft Powerpoint.Slide.8'。

```cpp
virtual void Aspose::Slides::Export::IPptOptions::set_RootDirectoryClsid(System::Guid value)=0
```

## 備註



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```

## 另請參閱

* 類別 [Guid](../../../system/guid/)
* 類別 [IPptOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)