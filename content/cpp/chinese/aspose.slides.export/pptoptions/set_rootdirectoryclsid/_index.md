---
title: set_RootDirectoryClsid()
second_title: Aspose.Slides for C++ API 参考
description: 表示存储在根目录项中的对象类 GUID（CLSID）。 可用于对文档的应用程序进行 COM 激活。 默认值为 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，对应于 'Microsoft Powerpoint.Slide.8'。
type: docs
weight: 14
url: /zh/aspose.slides.export/pptoptions/set_rootdirectoryclsid/
---
## PptOptions::set_RootDirectoryClsid(System::Guid) 方法


表示存储在根目录项中的对象类 GUID（CLSID）。 可用于对文档应用程序进行 COM 激活。 默认值为 '64818D11-4F9B-11CF-86EA-00AA00B929E8'，它对应于 'Microsoft Powerpoint.Slide.8'。

```cpp
void Aspose::Slides::Export::PptOptions::set_RootDirectoryClsid(System::Guid value) override
```

## 备注



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PptOptions> pptOptions = System::MakeObject<PptOptions>();

pptOptions->set_RootDirectoryClsid(System::Guid(u"64818D10-4F9B-11CF-86EA-00AA00B929E8"));

pres->Save(u"pres.ppt", Aspose::Slides::Export::SaveFormat::Ppt, pptOptions);
```




## 另请参见

* 类 [Guid](../../../system/guid/)
* 类 [PptOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)