---
title: set_DocumentLevelFontSources()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションと共有されません
type: docs
weight: 222
url: /ja/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) メソッド

プレゼンテーションで使用される外部フォントのソースを指定します。これらのフォントはプレゼンテーションの存続期間中利用可能で、他のプレゼンテーションと共有されません。

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## 備考

次の例は、PowerPoint [Presentation](../../presentation/)で使用されるカスタムフォントを指定する方法を示しています。

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// プレゼンテーションで作業します
// CustomFont1、CustomFont2 と assets\fonts および global\fonts フォルダーとそのサブフォルダーのフォントはプレゼンテーションで使用可能です
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IFontSources](../../ifontsources/)
* クラス [LoadOptions](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)