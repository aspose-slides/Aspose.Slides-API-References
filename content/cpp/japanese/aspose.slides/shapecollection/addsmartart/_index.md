---
title: AddSmartArt()
second_title: Aspose.Slides for C++ API リファレンス
description: SmartArt ダイアグラムを作成し、シェイプ コレクションの末尾に追加します。
type: docs
weight: 79
url: /ja/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) メソッド

[SmartArt](../../../aspose.slides.smartart/) ダイアグラムを作成し、シェイプ コレクションの末尾に追加します。

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | ダイアグラムのフレームの x 座標（ポイント単位）。 |
| y | **float** | ダイアグラムのフレームの y 座標（ポイント単位）。 |
| width | **float** | ダイアグラムのフレームの幅（ポイント単位）。 |
| height | **float** | ダイアグラムのフレームの高さ（ポイント単位）。 |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) のレイアウトタイプ。 |

### 戻り値

新しく作成された [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/)。

## 備考

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## 参照

* 列挙体 [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* クラス [ShapeCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)