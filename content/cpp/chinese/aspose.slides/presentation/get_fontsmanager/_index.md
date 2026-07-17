---
title: get_FontsManager()
second_title: Aspose.Slides for C++ API 参考
description: 返回字体管理器。只读 IFontsManager.
type: docs
weight: 157
url: /zh/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() 方法


返回字体管理器。只读 [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## 备注


下面的示例展示了如何向 PowerPoint [Presentation](../) 添加嵌入字体。 
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




## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IFontsManager](../../ifontsmanager/)
* 类 [Presentation](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)