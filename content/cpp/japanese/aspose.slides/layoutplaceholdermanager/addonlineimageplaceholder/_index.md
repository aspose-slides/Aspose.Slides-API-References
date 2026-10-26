---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウト スライドにオンライン画像を保持するための新しいプレースホルダー シェイプを追加します。
type: docs
weight: 118
url: /ja/aspose.slides/layoutplaceholdermanager/addonlineimageplaceholder/
---
## LayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) method

レイアウト スライドにオンライン画像を保持するための新しいプレースホルダー シェイプを追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダー シェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダー シェイプの幅です。 |
| height | **float** | 新しいプレースホルダー シェイプの高さです。 |

### 戻り値

オンライン画像プレースホルダー付きの [IAutoShape](../../iautoshape/) を作成しました。

## 備考

次の例は、レイアウト スライドにオンライン画像プレースホルダーシェイプを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)