---
title: AddMediaPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドにメディアオブジェクトを保持するための新しいプレースホルダーシェイプを追加します。
type: docs
weight: 105
url: /ja/aspose.slides/ilayoutplaceholdermanager/addmediaplaceholder/
---
## ILayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) メソッド

レイアウトスライドにメディアオブジェクトを保持するための新しいプレースホルダーシェイプを追加します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプのX座標です。 |
| y | **float** | 新しいプレースホルダーシェイプのY座標です。 |
| width | **float** | 新しいプレースホルダーシェイプの幅です。 |
| height | **float** | 新しいプレースホルダーシェイプの高さです。 |

### 戻り値

[IAutoShape](../../iautoshape/) を Media プレースホルダーで作成しました。

## 備考

以下の例は、レイアウトスライドに Media プレースホルダーシェイプを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddMediaPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)