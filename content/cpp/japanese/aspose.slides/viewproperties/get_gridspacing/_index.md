---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔をポイント単位で返します。float を読み取ります。
type: docs
weight: 92
url: /ja/aspose.slides/viewproperties/get_gridspacing/
---
## ViewProperties::get_GridSpacing() メソッド

プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔をポイント単位で返します。**float** を読み取ります。

```cpp
float Aspose::Slides::ViewProperties::get_GridSpacing() override
```

## 備考

グリッド間隔の値は正の数でなければなりません。典型的な値の範囲は 1 mm（2.8349607 ポイント）から 2 インチ（144 ポイント）です。

以下のサンプルコードは、PowerPoint プレゼンテーションでグリッド間隔を変更する方法を示しています。 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [ViewProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)