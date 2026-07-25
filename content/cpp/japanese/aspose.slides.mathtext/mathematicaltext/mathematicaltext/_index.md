---
title: MathematicalText()
second_title: Aspose.Slides for C++ API リファレンス
description: "デフォルトコンストラクタ（String::Empty 値を作成）"
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathematicaltext/mathematicaltext/
---
## MathematicalText::MathematicalText() コンストラクタ

デフォルトコンストラクタ (String::Empty 値を作成)

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText()
```

## 備考

例:
```cpp
auto mathText = System::MakeObject<MathematicalText>();
```

## MathematicalText::MathematicalText(char16_t) コンストラクタ

単一記号で [MathText](../../) を作成

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(char16_t mathSymbol)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char16_t | 単一記号 |

## 備考

例:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u'$');
```

## MathematicalText::MathematicalText(System::String) コンストラクタ

テキストから [MathematicalText](../) を作成

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | テキスト値 |

## 備考

例:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
```

## MathematicalText::MathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) コンストラクタ

テキストと書式設定から [MathematicalText](../) を作成

```cpp
Aspose::Slides::MathText::MathematicalText::MathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | テキスト値 |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | テキスト書式設定 |

## 備考

例:
```cpp
auto format = [&]{ auto tmp_0 = System::MakeObject<PortionFormat>(); tmp_0->set_FontHeight(12); return tmp_0; }();
auto mathText = System::MakeObject<MathematicalText>(u"x+y", format);
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathematicalText](../)
* Class [String](../../../system/string/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)