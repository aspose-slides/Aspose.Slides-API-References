---
title: AddTablePlaceholder()
second_title: Aspose.Slides for C++ API リファレンス
description: テーブルを保持するためにレイアウトスライドに新しいプレースホルダーシェイプを追加します。
type: docs
weight: 79
url: /ja/aspose.slides/layoutplaceholdermanager/addtableplaceholder/
---
## LayoutPlaceholderManager::AddTablePlaceholder(float, float, float, float) メソッド


レイアウトスライドにテーブルを保持するための新しいプレースホルダーシェイプを追加します。

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTablePlaceholder(float x, float y, float width, float height) override
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



次の例は、[Table](../../table/) プレースホルダーシェイプをレイアウトスライドに追加する方法を示します。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTablePlaceholder(20.0f, 20.0f, 500.0f, 200.0f);
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IAutoShape](../../iautoshape/)
* クラス [LayoutPlaceholderManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)