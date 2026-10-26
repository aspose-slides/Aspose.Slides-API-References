---
title: set_TargetSection()
second_title: Aspose.Slides for C++ API リファレンス
description: Section Zoom オブジェクトがリンクされているセクション オブジェクトを設定します。ISection を書き込みます。
type: docs
weight: 14
url: /ja/aspose.slides/isectionzoomframe/set_targetsection/
---
## ISectionZoomFrame::set_TargetSection(System::SharedPtr\<ISection\>) メソッド

[Section](../../section/) Zoom オブジェクトがリンクされているセクション オブジェクトを設定します。[ISection](../../isection/) を書き込みます。

```cpp
virtual void Aspose::Slides::ISectionZoomFrame::set_TargetSection(System::SharedPtr<ISection> value)=0
```

## 備考

この例では、対象セクションの変更を示し、セクション ズーム オブジェクトの新しい画像を作成します:
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
* Library [Aspose.Slides](../../../)