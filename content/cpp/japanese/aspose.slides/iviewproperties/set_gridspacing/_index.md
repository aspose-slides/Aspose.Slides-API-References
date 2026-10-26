---
title: set_GridSpacing()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション ドキュメントの基礎となるグリッドに使用すべきグリッド間隔をポイント単位で設定します。float を書き込みます。
type: docs
weight: 105
url: /ja/aspose.slides/iviewproperties/set_gridspacing/
---
## IViewProperties::set_GridSpacing(float) メソッド

プレゼンテーション ドキュメントの基礎となるグリッドに使用すべきグリッド間隔をポイント単位で設定します。**float**を書き込みます。

```cpp
virtual void Aspose::Slides::IViewProperties::set_GridSpacing(float value)=0
```

## 備考

グリッド間隔の値は正の数でなければなりません。典型的な値の範囲は 1 mm (2.8349607 ポイント) から 2 インチ (144 ポイント) です。

次のサンプルコードは、PowerPoint プレゼンテーションでグリッド間隔を変更する方法を示しています。
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();
pres->get_ViewProperties()->set_GridSpacing(72.0f);
pres->Save(u"GridSpacing_out.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [IViewProperties](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)