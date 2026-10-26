---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides for C++ API 參考
description: 指定用於簡報的外部字型來源。這些字型在簡報的整個生命週期內可供使用，且不會與其他簡報共享
type: docs
weight: 209
url: /zh-hant/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() 方法


指定用於簡報的外部字型來源。這些字型在簡報的整個生命週期內可供使用，且不會與其他簡報共享

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## 備註


以下範例說明如何指定在 PowerPoint [Presentation](../../presentation/) 中使用的自訂字型。 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// 操作簡報
// CustomFont1、CustomFont2 以及來自 assets\fonts & global\fonts 資料夾及其子資料夾的字型均可供簡報使用
```

## 參見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IFontSources](../../ifontsources/)
* 類別 [LoadOptions](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)