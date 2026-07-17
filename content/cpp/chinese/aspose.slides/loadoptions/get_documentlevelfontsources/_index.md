---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides C++ API 参考
description: 指定用于演示文稿的外部字体来源。这些字体在演示文稿的整个生命周期内可用，并且不会与其他演示文稿共享。
type: docs
weight: 209
url: /zh/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() 方法

指定在演示文稿中使用的外部字体来源。这些字体在演示文稿的整个生命周期内可用，并且不会与其他演示文稿共享。

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## 备注

以下示例展示了如何指定在 PowerPoint [Presentation](../../presentation/) 中使用的自定义字体。

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// 对演示文稿进行操作
// CustomFont1、CustomFont2 以及来自 assets\fonts & global\fonts 文件夹及其子文件夹的字体可用于演示文稿
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IFontSources](../../ifontsources/)
* 类 [LoadOptions](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)