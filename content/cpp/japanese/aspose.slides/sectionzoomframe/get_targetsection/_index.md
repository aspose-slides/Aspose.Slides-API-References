---
title: get_TargetSection()
second_title: Aspose.Slides の C++ API リファレンス
description: Section Zoom オブジェクトがリンクしているセクション オブジェクトを取得します。ISection を参照してください。
type: docs
weight: 1
url: /ja/aspose.slides/sectionzoomframe/get_targetsection/
---
## SectionZoomFrame::get_TargetSection() メソッド

[Section](../../section/) Zoom オブジェクトがリンクしているセクション オブジェクトを取得します。[ISection](../../isection/) を参照してください。

```cpp
System::SharedPtr<ISection> Aspose::Slides::SectionZoomFrame::get_TargetSection() override
```

## 備考

次の例は、対象セクションの変更とセクション ズーム オブジェクトの新しい画像の作成を示します:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISection](../../isection/)
* クラス [SectionZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)