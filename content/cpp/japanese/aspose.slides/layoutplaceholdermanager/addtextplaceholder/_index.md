---
title: AddTextPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウト スライドにテキスト コンテンツを保持する新しいプレースホルダー シェイプを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) メソッド


テキスト コンテンツを保持するために、レイアウト スライドに新しいプレースホルダー シェイプを追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダー シェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダー シェイプの幅です。 |
| height | **float** | 新しいプレースホルダー シェイプの高さです。 |

### 戻り値

[IAutoShape](../../iautoshape/) をテキスト プレースホルダーとして作成しました。

## 備考



次の例は、レイアウト スライドに Text プレースホルダー シェイプを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)