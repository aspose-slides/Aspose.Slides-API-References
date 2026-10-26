---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartArt 図を作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 40
url: /ja/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) メソッド

[SmartArt](../../../aspose.slides.smartart/) 図を作成し、シェイプ コレクションの末尾に追加します。

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 図のフレームの x 座標（ポイント単位）。 |
| y | **float** | 図のフレームの y 座標（ポイント単位）。 |
| width | **float** | 図のフレームの幅（ポイント単位）。 |
| height | **float** | 図のフレームの高さ（ポイント単位）。 |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) のレイアウト タイプ。 |

### 戻り値

新しく作成された [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)。

## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## 参照

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)