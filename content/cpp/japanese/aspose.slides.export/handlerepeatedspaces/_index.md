---
title: HandleRepeatedSpaces
second_title: Aspose.Slides for C++ API リファレンス
description: Markdown エクスポート時に、連続する通常のスペース文字をどのように処理するかを指定します。
type: docs
weight: 937
url: /ja/aspose.slides.export/handlerepeatedspaces/
---
## HandleRepeatedSpaces 列挙型


Markdown エクスポート時に、連続する通常のスペース文字をどのように処理するかを指定します。

```cpp
enum class HandleRepeatedSpaces
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | 0 | すべてのスペースは変更せずに通常のスペース文字として保持されます。変換は行われず、連続した複数のスペースはそのままエクスポートされます。 |
| AlternateSpacesToNbsp | 1 | 2 つ以上連続する通常のスペースのシーケンスを、通常のスペース文字とノーブレークスペースエンティティ (**&nbsp;**) を交互に置き換えて変換します。最初のスペースは常に通常のスペースとして保持されます。 |
| MultipleSpacesToNbsp | 2 | 2 つ以上連続する通常のスペースのシーケンスを、最初のスペースを通常のスペース文字として保持し、以降のすべてのスペースをノーブレークスペースエンティティ (**&nbsp;**) に置き換えて変換します。 |

## 参照

* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)