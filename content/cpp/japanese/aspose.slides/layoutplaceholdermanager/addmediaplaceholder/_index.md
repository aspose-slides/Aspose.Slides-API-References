---
title: AddMediaPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドにメディアオブジェクトを保持する新しいプレースホルダーシェイプを追加します。
type: docs
weight: 105
url: /ja/aspose.slides/layoutplaceholdermanager/addmediaplaceholder/
---
## LayoutPlaceholderManager::AddMediaPlaceholder(float, float, float, float) メソッド

レイアウトスライドにメディアオブジェクトを保持する新しいプレースホルダーシェイプを追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddMediaPlaceholder(float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標です。 |
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

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)