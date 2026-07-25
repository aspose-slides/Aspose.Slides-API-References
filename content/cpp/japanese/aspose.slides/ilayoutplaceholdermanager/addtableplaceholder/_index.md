---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: レイアウトスライドにテーブルを保持するための新しいプレースホルダー シェイプを追加します。
type: docs
weight: 79
url: /ja/aspose.slides/ilayoutplaceholdermanager/addtableplaceholder/
---
## ILayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) メソッド

レイアウトスライドにテーブルを保持するための新しいプレースホルダー シェイプを追加します。

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| x | **float** | 新しいプレースホルダーシェイプの X 座標。 |
| y | **float** | 新しいプレースホルダーシェイプの Y 座標。 |
| width | **float** | 新しいプレースホルダーシェイプの幅。 |
| height | **float** | 新しいプレースホルダーシェイプの高さ。 |

### 戻り値

[IAutoShape](../../iautoshape/) が [Table](../../table/) プレースホルダーで作成されました。

## 備考

次の例は、レイアウトスライドに [Table](../../table/) プレースホルダーシェイプを追加する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [ILayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)