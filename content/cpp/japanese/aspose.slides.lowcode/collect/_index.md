---
title: Collect
second_title: Aspose.Slides for C++ API リファレンス
description: Presentation からさまざまなタイプのモデルオブジェクトを収集することを目的としたメソッドのグループを表します。
type: docs
weight: 1
url: /ja/aspose.slides.lowcode/collect/
---
## Collect クラス

さまざまな型のモデルオブジェクトを [Presentation](../../aspose.slides/presentation/) から収集することを目的としたメソッドのグループを表します。

```cpp
class Collect
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | [Presentation](../../aspose.slides/presentation/) 内のすべての [Shape](../../aspose.slides/shape/) インスタンスを収集します。 |
## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... シェイプの書式設定やその他のプロパティを変更します
}
```

## 参照

* 名前空間 [Aspose::Slides::LowCode](../)
* ライブラリ [Aspose.Slides](../../)