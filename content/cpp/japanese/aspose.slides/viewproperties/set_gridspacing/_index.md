---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション文書の基になるグリッドに使用すべきグリッド間隔をポイント単位で設定します。floatを書き込みます。
type: docs
weight: 105
url: /ja/aspose.slides/viewproperties/set_gridspacing/
---
## ViewProperties::set_GridSpacing(float) メソッド


プレゼンテーション文書の基になるグリッドに使用すべきグリッド間隔をポイント単位で設定します。**float** を書き込みます。

```cpp
void Aspose::Slides::ViewProperties::set_GridSpacing(float value) override
```

## 備考


グリッド間隔の値は正の数でなければなりません。典型的な値の範囲は 1 mm（2.8349607 ポイント）から 2 インチ（144 ポイント）です。

次のサンプルコードは、PowerPoint プレゼンテーションでグリッド間隔を変更する方法を示しています。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [ViewProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)