---
title: get_MasterTheme()
second_title: Aspose.Slides for C++ API リファレンス
description: "マスターテーマを返します。読み取り専用 Theme::IMasterTheme."
type: docs
weight: 404
url: /ja/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() メソッド


マスターテーマを返します。読み取り専用 [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## 備考


次の例は、PowerPoint [Presentation](../) の要素の一部を変更することでテーマ効果を変更する方法を示しています。 
```cpp
// プレゼンテーションファイルを表すプレゼンテーションオブジェクトをインスタンス化します
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)