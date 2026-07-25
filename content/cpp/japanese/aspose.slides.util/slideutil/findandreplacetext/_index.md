---
title: FindAndReplaceText()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション内のテキストを検索し、指定された形式で置換します
type: docs
weight: 40
url: /ja/aspose.slides.util/slideutil/findandreplacetext/
---
## SlideUtil::FindAndReplaceText(System::SharedPtr\<IPresentation\>, bool, System::String, System::String, System::SharedPtr\<PortionFormat\>) メソッド

プレゼンテーション内のテキストを検索して、指定されたフォーマットで置換します。

```cpp
static void Aspose::Slides::Util::SlideUtil::FindAndReplaceText(System::SharedPtr<IPresentation> presentation, bool withMasters, System::String find, System::String replace, System::SharedPtr<PortionFormat> format=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| presentation | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | スキャンされたプレゼンテーション。 |
| withMasters | **bool** | マスタースライドをスキャンするかどうかを決定します。 |
| find | [System::String](../../../system/string/) | 検索する文字列値。 |
| replace | [System::String](../../../system/string/) | 置換する文字列値。 |
| format | [System::SharedPtr](../../../system/sharedptr/)\<[PortionFormat](../../../aspose.slides/portionformat/)\> | テキスト部分を置換するためのフォーマット。null の場合、見つかった文字列の最初の文字のフォーマットが使用されます。 |

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto format = System::MakeObject<PortionFormat>();
format->set_FontHeight(24.0f);
format->set_FontItalic(NullableBool::True);
auto fillFormat = format->get_FillFormat();
fillFormat->set_FillType(FillType::Solid);
fillFormat->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());

SlideUtil::FindAndReplaceText(pres, true, u"[this block] ", u"my text ", format);
pres->Save(u"replaced", SaveFormat::Pptx);
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPresentation](../../../aspose.slides/ipresentation/)
* クラス [String](../../../system/string/)
* クラス [PortionFormat](../../../aspose.slides/portionformat/)
* クラス [SlideUtil](../)
* 名前空間 [Aspose::Slides::Util](../../)
* ライブラリ [Aspose.Slides](../../../)