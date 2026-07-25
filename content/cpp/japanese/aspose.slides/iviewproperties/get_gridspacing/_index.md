---
title: get_GridSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔（ポイント単位）を返します。読み取り float.
type: docs
weight: 92
url: /ja/aspose.slides/iviewproperties/get_gridspacing/
---
## IViewProperties::get_GridSpacing() メソッド

プレゼンテーション ドキュメントの基になるグリッドに使用すべきグリッド間隔（ポイント単位）を返します。読み取り **float**。

```cpp
virtual float Aspose::Slides::IViewProperties::get_GridSpacing()=0
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

* クラス [IViewProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)