---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
段落のインデントと MarginLeft に対して、箇条書きが有効な場合にデフォルトの非ゼロシフトを設定します（PowerPoint が段落の箇条書き/番号付けを有効にしたときの動作と同様）。箇条書きが無効な場合は、段落のインデントと MarginLeft をリセットします（PowerPoint が段落の箇条書き/番号付けを無効にしたときの動作と同様）。インデントシフトは現在の箇条書きコンテキスト（IBulletFormat.Type、.NumberedBulletStyle、最初の部分の FontHeight）に基づいて適用されます。非ゼロのインデントシフトは、現在の段落の有効な Indent と MarginLeft に適用され、結果の値がローカル値になるようにします。

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | このメソッドの呼び出しは、次の場合に **System.InvalidOperationException** をスローします。<br/>            親の書式設定オブジェクトが段落でない場合（例：ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() を呼び出すと例外がスローされます）；<br/>            または段落が任意の ITextFrame.Paragraphs コレクションに追加されていない場合（最初に追加してください）； |

### See Also
* class [`BulletFormat`](/slides/python-net/ja/aspose.slides/bulletformat)
* module [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)