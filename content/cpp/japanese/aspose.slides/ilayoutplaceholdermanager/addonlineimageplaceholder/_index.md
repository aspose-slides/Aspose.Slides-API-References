---
title: AddOnlineImagePlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドにオンライン画像を保持するための新しいプレースホルダーシェイプを追加します。
type: docs
weight: 118
url: /ja/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) メソッド

レイアウトスライドにオンライン画像を保持するための新しいプレースホルダーシェイプを追加します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダーシェイプの幅です。 |
| height | **float** | 新しいプレースホルダーシェイプの高さです。 |

### Return Value

[IAutoShape](../../iautoshape/) をオンライン画像プレースホルダーとして作成しました。

## 備考

次の例は、レイアウトスライドにオンライン画像プレースホルダーシェイプを追加する方法を示しています。

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)