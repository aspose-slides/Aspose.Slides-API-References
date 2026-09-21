---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
設定當啟用項目符號時（如 PowerPoint 在啟用段落項目符號/編號時的行為），對有效段落的 Indent 與 MarginLeft 設定預設的非零位移。若項目符號停用，則僅重設段落的 Indent 與 MarginLeft（如 PowerPoint 在停用段落項目符號/編號時的行為）。位移會根據目前的項目符號環境 - IBulletFormat.Type、.NumberedBulletStyle 以及第一段文字的 FontHeight 來套用。非零位移會套用到目前段落的有效 Indent 與 MarginLeft（使結果值為局部值）。

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 呼叫此方法不會有影響，且在以下情況下拋出 **System.InvalidOperationException**：<br/>            如果父層格式化對象不是段落（例如呼叫 ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() 會拋出例外）；<br/>            或者段落尚未加入任何 ITextFrame.Paragraphs 集合（先加入它）； |

### 另見
* 類別 [`IBulletFormat`](/slides/python-net/zh-hant/aspose.slides/ibulletformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)