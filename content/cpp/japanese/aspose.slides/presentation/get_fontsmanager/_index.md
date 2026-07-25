---
title: get_FontsManager()
second_title: Aspose.Slides for C++ API リファレンス
description: フォントマネージャーを返します。読み取り専用 IFontsManager.
type: docs
weight: 157
url: /ja/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() メソッド

フォントマネージャーを返します。読み取り専用 [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## 備考

次の例では、PowerPoint [Presentation](../) に埋め込みフォントを追加する方法を示します。
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```



## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IFontsManager](../../ifontsmanager/)
* クラス [Presentation](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)