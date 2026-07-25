---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドに新しいプレースホルダーシェイプを追加し、画像、テーブル、メディア、テキストなどのコンテンツを垂直方向に保持します。
type: docs
weight: 14
url: /ja/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) メソッド

新しいプレースホルダーシェイプをレイアウトスライドに追加し、画像、テーブル、メディア、テキストなどのコンテンツを垂直方向に保持します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標。 |
| width | **float** | 新しいプレースホルダーシェイプの幅。 |
| height | **float** | 新しいプレースホルダーシェイプの高さ。 |

### 戻り値

Created [IAutoShape](../../iautoshape/) with a Content (Vertical) placeholder.

## 備考

以下の例は、レイアウトスライドに Content (Vertical) プレースホルダーシェイプを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)