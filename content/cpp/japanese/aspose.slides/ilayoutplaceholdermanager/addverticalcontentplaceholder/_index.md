---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウト スライドに新しいプレースホルダー シェイプを追加し、画像、テーブル、メディア、またはテキストなどのコンテンツを縦方向で保持します。
type: docs
weight: 14
url: /ja/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) メソッド

新しいプレースホルダー シェイプをレイアウト スライドに追加し、画像、テーブル、メディア、またはテキストなどのコンテンツを縦方向で保持します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダー シェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダー シェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダー シェイプの幅です。 |
| height | **float** | 新しいプレースホルダー シェイプの高さです。 |

### 戻り値

コンテンツ (縦方向) プレースホルダーを使用して [IAutoShape](../../iautoshape/) を作成しました。

## 備考

次の例は、レイアウト スライドにコンテンツ (縦方向) プレースホルダー シェイプを追加する方法を示しています。

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)