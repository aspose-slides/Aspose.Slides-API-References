---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウト スライドに新しいプレースホルダー シェイプを追加し、画像、テーブル、メディア、テキストなどのコンテンツを保持します。
type: docs
weight: 1
url: /ja/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) method


レイアウト スライドに新しいプレースホルダー シェイプを追加し、画像、テーブル、メディア、テキストなどのコンテンツを保持します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダー シェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダー シェイプの幅です。 |
| height | **float** | 新しいプレースホルダー シェイプの高さです。 |

### 戻り値

Content プレースホルダーを持つ [IAutoShape](../../iautoshape/) を作成しました。

## 備考



次の例は、レイアウト スライドに Content プレースホルダー シェイプを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)