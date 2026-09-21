---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
當啟用項目符號 (bullets) 時，設定有效段落 Indent 和 MarginLeft 的預設非零位移 (如 PowerPoint 在啟用段落項目符號/編號時的做法)。若停用項目符號，則僅重設段落 Indent 和 MarginLeft (如 PowerPoint 在停用段落項目符號/編號時的做法)。位移根據目前的項目符號上下文 - IBulletFormat.Type、.NumberedBulletStyle 以及第一段文字的 FontHeight 來套用。非零位移將套用到目前段落的有效 Indent 和 MarginLeft (使結果值為局部值)。

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 呼叫此方法無關緊要，且在以下情況下拋出 **System.InvalidOperationException**：<br/>            如果父格式化物件不是段落（例如呼叫 ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() 會拋出例外）；<br/>            或者段落尚未加入任何 ITextFrame.Paragraphs 集合（請先加入）； |

### 另請參閱
* 類別 [`BulletFormat`](/slides/python-net/zh-hant/aspose.slides/bulletformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)