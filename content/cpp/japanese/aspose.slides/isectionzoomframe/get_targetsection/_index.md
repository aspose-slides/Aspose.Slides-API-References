---
title: get_TargetSection()
second_title: Aspose.Slides for C++ API リファレンス
description: Section Zoom オブジェクトがリンクされているセクション オブジェクトを取得します。ISection を参照してください。
type: docs
weight: 1
url: /ja/aspose.slides/isectionzoomframe/get_targetsection/
---
## ISectionZoomFrame::get_TargetSection() メソッド

[Section](../../section/) Zoom オブジェクトがリンクされているセクション オブジェクトを取得します。[ISection](../../isection/) を参照してください。

```cpp
virtual System::SharedPtr<ISection> Aspose::Slides::ISectionZoomFrame::get_TargetSection()=0
```

## 備考

この例は、ターゲット セクションを変更し、セクション ズーム オブジェクトの新しい画像を作成することを示しています。  
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto sectionZoomFrame = shapes->AddSectionZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Sections()->idx_get(1));
sectionZoomFrame->set_TargetSection(pres->get_Sections()->idx_get(2));
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [ISection](../../isection/)
* クラス [ISectionZoomFrame](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)