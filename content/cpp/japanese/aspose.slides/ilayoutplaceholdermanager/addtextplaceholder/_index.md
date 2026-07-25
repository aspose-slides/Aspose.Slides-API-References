---
title: AddTextPlaceholder()
second_title: Aspose.Slides の C++ API リファレンス
description: レイアウトスライドにテキストコンテンツを保持する新しいプレースホルダーシェイプを追加します。
type: docs
weight: 27
url: /ja/aspose.slides/ilayoutplaceholdermanager/addtextplaceholder/
---
## ILayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) メソッド


レイアウトスライドにテキストコンテンツを保持するための新しいプレースホルダーシェイプを追加します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標です。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標です。 |
| width | **float** | 新しいプレースホルダーシェイプの幅です。 |
| height | **float** | 新しいプレースホルダーシェイプの高さです。 |


### 戻り値

Text プレースホルダーを使用して [IAutoShape](../../iautoshape/) が作成されました。

## 備考


次の例は、レイアウトスライドに Text プレースホルダーシェイプを追加する方法を示しています。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)