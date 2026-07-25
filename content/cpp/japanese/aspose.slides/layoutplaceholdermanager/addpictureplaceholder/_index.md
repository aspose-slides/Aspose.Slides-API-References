---
title: AddPicturePlaceholder()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 画像を保持するために、レイアウト スライドに新しいプレースホルダー シェイプを追加します。
type: docs
weight: 53
url: /ja/aspose.slides/layoutplaceholdermanager/addpictureplaceholder/
---
## LayoutPlaceholderManager::AddPicturePlaceholder(float, float, float, float) メソッド

レイアウト スライドに画像を保持するための新しいプレースホルダー シェイプを追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddPicturePlaceholder(float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダー シェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダー シェイプの幅です。 |
| height | **float** | 新しいプレースホルダー シェイプの高さです。 |

### 戻り値

作成された [IAutoShape](../../iautoshape/) に [Picture](../../picture/) プレースホルダーが付与されました。

## 備考

次の例は、[Picture](../../picture/) プレースホルダー シェイプをレイアウト スライドに追加する方法を示しています。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddPicturePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)