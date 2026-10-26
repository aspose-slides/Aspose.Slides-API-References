---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides for C++ API リファレンス
description: "箇条書きが有効な場合、実際の段落の Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します（PowerPoint が段落の箇条書き/番号付きを有効にしたときと同様です）。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付きを無効にしたときと同様です）。インデントシフトは現在の箇条書きコンテキスト、つまり IBulletFormat::get(set)_Type、.NumberedBulletStyle、最初の部分の FontHeight を基準に適用されます。非ゼロのインデントシフトは現在の段落の実際の Indent と MarginLeft に適用され、結果の値はローカル値になります。"
type: docs
weight: 235
url: /ja/aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() メソッド

箇条書きが有効な場合（PowerPoint が段落の箇条書き/番号付きを有効にしたときと同様）、有効な段落の Indent および MarginLeft に対してデフォルトの非ゼロシフトを設定します。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付きを無効にしたときと同様）。インデントシフトは現在の箇条書きコンテキスト、すなわち IBulletFormat::get(set)_Type、.NumberedBulletStyle、最初の部分の FontHeight を基準に適用されます。非ゼロのインデントシフトは現在の段落の有効な Indent と MarginLeft に適用され、結果の値はローカル値になります。

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```

## 参照

* クラス [IBulletFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)