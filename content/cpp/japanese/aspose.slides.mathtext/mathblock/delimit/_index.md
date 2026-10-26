---
title: Delimit()
second_title: Aspose.Slides for C++ API リファレンス
description: 子要素を区切り文字で区切ります（角括弧は含みません）
type: docs
weight: 209
url: /ja/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) メソッド


区切り文字で子要素を区切ります（角括弧は含みません）

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| separatorCharacter | char16_t | 区切り文字 |

### 戻り値

タイプ[IMathDelimiter](../../imathdelimiter/)の数式要素
## 備考



例：
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathDelimiter](../../imathdelimiter/)
* クラス [MathBlock](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)