---
title: set_HandleRepeatedSpaces()
second_title: Aspose.Slides for C++ API リファレンス
description: Markdown エクスポート中に繰り返しの通常スペース文字をどのように処理するかを指定します。
type: docs
weight: 248
url: /ja/aspose.slides.export/markdownsaveoptions/set_handlerepeatedspaces/
---
## MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces) メソッド


Markdown エクスポート中に繰り返しの通常スペース文字をどのように処理するかを指定します。

```cpp
void Aspose::Slides::Export::MarkdownSaveOptions::set_HandleRepeatedSpaces(Aspose::Slides::Export::HandleRepeatedSpaces value)
```

## 備考


このプロパティは、連続したスペースが以下のどれであるかを定義します:* 通常のスペース文字として保持される,
* 通常のスペースとノーブレークスペースエンティティ (**&nbsp;**) を交互に使用する,
* 最初のスペース以降、**&nbsp;** に完全に置き換えられ、Markdown 出力で視覚的配置を保つ.



デフォルト値は [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/)です。 
## 参照

* 列挙体 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* クラス [MarkdownSaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)