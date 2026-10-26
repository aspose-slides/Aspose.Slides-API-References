---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides for C++ API リファレンス
description: "箇条書きが有効な場合、実際の段落の Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します（PowerPoint で段落の箇条書き/番号付けを有効にした場合と同様です）。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットするだけです（PowerPoint で段落の箇条書き/番号付けを無効にした場合と同様です）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat::get(set)_Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは現在の段落の実際の Indent と MarginLeft に適用され、結果の値をローカル値にします。"
type: docs
weight: 235
url: /ja/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() メソッド

箇条書きが有効な場合、実際の段落の Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します（PowerPoint が段落の箇条書き/番号付けを有効にした場合と同様）。箇条書きが無効な場合は、段落の Indent と MarginLeft をリセットするだけです（PowerPoint が段落の箇条書き/番号付けを無効にした場合と同様）。インデントシフトは現在の箇条書きコンテキスト - IBulletFormat::get(set)_Type、.NumberedBulletStyle および最初の部分の FontHeight に基づいて適用されます。非ゼロのインデントシフトは現在の段落の実際の Indent と MarginLeft に適用され、結果の値をローカル値にします。

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```

## 参照

* クラス [BulletFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)