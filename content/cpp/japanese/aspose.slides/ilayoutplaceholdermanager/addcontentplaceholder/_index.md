---
title: AddContentPlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドに新しいプレースホルダーシェイプを追加し、画像、表、メディア、テキストなどのコンテンツを保持します。
type: docs
weight: 1
url: /ja/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) メソッド

レイアウトスライドに新しいプレースホルダーシェイプを追加し、画像、表、メディア、テキストなどのコンテンツを保持します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダーシェイプの幅です。 |
| height | **float** | 新しいプレースホルダーシェイプの高さです。 |

### 戻り値

[IAutoShape](../../iautoshape/) がコンテンツ プレースホルダーで作成されました。
## 備考

次の例は、レイアウトスライドにコンテンツ プレースホルダーシェイプを追加する方法を示しています。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)