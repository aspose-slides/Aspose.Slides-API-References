---
title: AddSmartArtPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドに新しいプレースホルダーシェイプを追加し、SmartArt 図を保持します。
type: docs
weight: 92
url: /ja/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) メソッド

レイアウトスライドに新しいプレースホルダーシェイプを追加して、[SmartArt](../../../aspose.slides.smartart/) 図を保持します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標。 |
| width | **float** | 新しいプレースホルダーシェイプの幅。 |
| height | **float** | 新しいプレースホルダーシェイプの高さ。 |

### 戻り値

[IAutoShape](../../iautoshape/) を作成し、[SmartArt](../../../aspose.slides.smartart/) プレースホルダーを使用しました。

## 備考

次の例は、[SmartArt](../../../aspose.slides.smartart/) プレースホルダーシェイプをレイアウトスライドに追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)