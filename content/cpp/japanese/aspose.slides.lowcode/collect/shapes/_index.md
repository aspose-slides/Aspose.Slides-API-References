---
title: Shapes()
second_title: Aspose.Slides の C++ API リファレンス
description: Presentation 内の Shape のすべてのインスタンスを収集します。
type: docs
weight: 1
url: /ja/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) メソッド


[Presentation](../../../aspose.slides/presentation/)にある[Shape](../../../aspose.slides/shape/)のすべてのインスタンスを収集します。

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/)シェイプを収集する |

### 戻り値

プレゼンテーションに含まれるすべてのシェイプのコレクション
## 備考




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // shape が AutoShape の場合、黒の実線の境界線を追加します
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```




## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [Shape](../../../aspose.slides/shape/)
* クラス [Presentation](../../../aspose.slides/presentation/)
* クラス [Collect](../)
* 名前空間 [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)