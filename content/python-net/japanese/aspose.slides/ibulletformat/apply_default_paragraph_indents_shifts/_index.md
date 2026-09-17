---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
箇条書きが有効な場合に、実際の段落 Indent と MarginLeft に対してデフォルトの非ゼロシフトを設定します（PowerPoint が段落の箇条書き/番号付けを有効にしたときの動作と同様です）。箇条書きが無効な場合は、段落 Indent と MarginLeft をリセットするだけです（PowerPoint が段落の箇条書き/番号付けを無効にしたときの動作と同様です）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは現在の段落の実際の Indent と MarginLeft に適用され、結果の値はローカル値となります。

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | このメソッドを呼び出すと、以下の場合に **System.InvalidOperationException** がスローされます（**RuntimeError(Proxy error(InvalidOperationException))** が発生します）。<br/>            親の書式設定オブジェクトが段落でない場合（例：ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() を呼び出すと例外がスローされます）；<br/>            または段落が ITextFrame.Paragraphs コレクションに追加されていない場合（最初に追加してください）； |

### 参照
* クラス [`IBulletFormat`](/slides/python-net/ja/aspose.slides/ibulletformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)