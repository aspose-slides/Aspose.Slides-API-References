---
title: Delimit()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された区切り文字を使用して引数を区切ります
type: docs
weight: 144
url: /ja/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) メソッド

指定された区切り文字を使用して引数を区切ります

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char16_t | 区切り文字 |

### 戻り値

区切り文字を適用した後のこのオブジェクト

## 備考



例: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)