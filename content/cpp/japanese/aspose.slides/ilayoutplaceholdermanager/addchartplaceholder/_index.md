---
title: AddChartPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウト スライドにチャートを保持するための新しいプレースホルダー シェイプを追加します。
type: docs
weight: 66
url: /ja/aspose.slides/ilayoutplaceholdermanager/addchartplaceholder/
---
## ILayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) メソッド

チャートを保持するために、レイアウト スライドに新しいプレースホルダー シェイプを追加します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダー シェイプの X 座標。 |
| y | **float** | 新しいプレースホルダー シェイプの Y 座標。 |
| width | **float** | 新しいプレースホルダー シェイプの幅。 |
| height | **float** | 新しいプレースホルダー シェイプの高さ。 |

### 戻り値

[IAutoShape](../../iautoshape/) を Chart プレースホルダーで作成しました。

## 備考

以下の例は、Chart プレースホルダー シェイプをレイアウト スライドに追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)