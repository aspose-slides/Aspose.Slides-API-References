---
title: get_InkEffect()
second_title: Aspose.Slides for C++ API リファレンス
description: "インクストロークの視覚スタイルを定義するインク効果タイプ（例: Galaxy、Gold、Silver）を取得します。値はブラシプロパティ \"inkEffects\" から解析されます。認識された効果が指定されない場合、InkEffectType::NotDefined が返されます。"
type: docs
weight: 53
url: /ja/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() メソッド


インク効果タイプ（例: Galaxy、Gold、Silver）を取得します。このタイプはインクストロークの視覚スタイルを定義します。値はブラシプロパティ「inkEffects」から解析されます。認識できない効果が指定された場合、[InkEffectType::NotDefined](../../inkeffecttype/) が返されます。

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## 備考


例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## 参照

* Enum [InkEffectType](../../inkeffecttype/)
* クラス [IInkBrush](../)
* 名前空間 [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)