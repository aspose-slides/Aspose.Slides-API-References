---
title: GetEffective()
second_title: Aspose.Slides for C++ API リファレンス
description: 継承が適用された有効な3-D書式設定データを取得します。
type: docs
weight: 183
url: /ja/aspose.slides/threedformat/geteffective/
---
## ThreeDFormat::GetEffective() メソッド

継承が適用された有効な3-D書式設定データを取得します。

```cpp
System::SharedPtr<IThreeDFormatEffectiveData> Aspose::Slides::ThreeDFormat::GetEffective() override
```

### 戻り値

[IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)。

## 備考


この例では、カメラ、ライトリグ、シェイプの上部ベベルの有効なプロパティを取得する方法を示しています。
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto threeDEffectiveData = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_ThreeDFormat()->GetEffective();

Console::WriteLine(u"= Effective camera properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_Camera()->get_CameraType()));
Console::WriteLine(String(u"Field of view: ") + threeDEffectiveData->get_Camera()->get_FieldOfViewAngle());
Console::WriteLine(String(u"Zoom: ") + threeDEffectiveData->get_Camera()->get_Zoom());

Console::WriteLine(u"= Effective light rig properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_LightType()));
Console::WriteLine(String(u"Direction: ") + ObjectExt::ToString(threeDEffectiveData->get_LightRig()->get_Direction()));

Console::WriteLine(u"= Effective shape's top face relief properties =");
Console::WriteLine(String(u"Type: ") + ObjectExt::ToString(threeDEffectiveData->get_BevelTop()->get_BevelType()));
Console::WriteLine(String(u"Width: ") + threeDEffectiveData->get_BevelTop()->get_Width());
Console::WriteLine(String(u"Height: ") + threeDEffectiveData->get_BevelTop()->get_Height());
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IThreeDFormatEffectiveData](../../ithreedformateffectivedata/)
* クラス [ThreeDFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)