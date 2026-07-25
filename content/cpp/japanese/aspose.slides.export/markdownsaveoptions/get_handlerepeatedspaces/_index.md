---
title: get_HandleRepeatedSpaces()
second_title: Aspose.Slides for C++ API リファレンス
description: Markdown エクスポート時に、繰り返される通常のスペース文字の処理方法を指定します。
type: docs
weight: 235
url: /ja/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const method

Markdown エクスポート時に、繰り返される通常のスペース文字の処理方法を指定します。

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## 備考

* 通常のスペース文字として保持されます,
* 通常のスペースとノーブレークスペースエンティティ (**&nbsp;**) を交互に使用します,
* または、Markdown 出力で視覚的な整列を保つために、最初のスペース以降をすべて **&nbsp;** に置き換えます。

デフォルト値は [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/) です。

## 参照

* 列挙型 [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* クラス [MarkdownSaveOptions](../)
* 名前空間 [Aspose::Slides::Export](../../)
* ライブラリ [Aspose.Slides](../../../)