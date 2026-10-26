---
title: Enclose()
second_title: Aspose.Slides for C++ API リファレンス
description: 数式要素を括弧やその他の文字など、指定された文字で枠付けします
type: docs
weight: 170
url: /ja/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) メソッド


指定された文字（括弧など）または別の文字で数式要素を枠付けします

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| beginningCharacter | char16_t | 開始文字（通常は左括弧） |
| endingCharacter | char16_t | 終了文字（通常は右括弧） |

### 戻り値

*beginningCharacter* と *endingCharacter* が null の場合、対応するプロパティに値が割り当てられるだけで新しいオブジェクトは作成されません（このインスタンスが返されます）。それ以外の場合、指定された文字で枠付けされた Delimiter 型の新しい数式要素が返され、[MathDelimiter](../) のインスタンスがその内部にフレームとして含まれます。

## 備考



例: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathDelimiter](../../imathdelimiter/)
* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)