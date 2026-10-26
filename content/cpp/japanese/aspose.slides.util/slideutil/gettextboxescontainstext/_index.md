---
title: GetTextBoxesContainsText()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたスライド上で、指定されたテキストを含むすべてのテキストフレームを返します。
type: docs
weight: 66
url: /ja/aspose.slides.util/slideutil/gettextboxescontainstext/
---
## SlideUtil::GetTextBoxesContainsText(System::SharedPtr\<IBaseSlide\>, System::String, bool) method


指定されたスライド上で、指定されたテキストを含むすべてのテキストフレームを返します。

```cpp
static System::ArrayPtr<System::SharedPtr<ITextFrame>> Aspose::Slides::Util::SlideUtil::GetTextBoxesContainsText(System::SharedPtr<IBaseSlide> slide, System::String text, bool checkPlaceholderText)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 検索対象のスライド。 |
| text | [System::String](../../../system/string/) | テキストフレーム内で検索するテキスト。 |
| checkPlaceholderText | **bool** | 空のテキストフレームであっても、プレースホルダー テキストに検索テキストが含まれている場合に含めるかどうかを示します。 |

### 戻り値

指定されたテキストを含む [ITextFrame](../../../aspose.slides/itextframe/) オブジェクトの配列。

## 関連項目

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [ITextFrame](../../../aspose.slides/itextframe/)
* クラス [IBaseSlide](../../../aspose.slides/ibaseslide/)
* クラス [String](../../../system/string/)
* クラス [SlideUtil](../)
* 名前空間 [Aspose::Slides::Util](../../)
* ライブラリ [Aspose.Slides](../../../)