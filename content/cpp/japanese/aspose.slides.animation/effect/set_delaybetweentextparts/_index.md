---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーションテキスト部分（単語または文字）間の遅延を定義します。正の値はエフェクト期間のパーセンテージを指定します。負の値は秒単位で遅延を指定します。float を書き込みます。
type: docs
weight: 313
url: /ja/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) メソッド

アニメーションテキスト部分（単語または文字）間の遅延を定義します。正の値はエフェクト期間のパーセンテージを指定します。負の値は秒単位で遅延を指定します。**float**を書き込みます。

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## 備考



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 最初のスライドの最初のエフェクトを取得します。
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// エフェクトのアニメーションテキストタイプを "By word" に変更します。
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// アニメーションテキスト部分間の遅延をエフェクト期間の 20% に設定します。
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 参照

* クラス [Effect](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)