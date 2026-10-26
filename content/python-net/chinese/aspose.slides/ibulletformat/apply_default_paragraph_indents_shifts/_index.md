---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
在启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时的行为），为有效的段落 Indent 和 MarginLeft 设置默认的非零偏移。如果禁用项目符号，则仅重置段落的 Indent 和 MarginLeft（如 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移会依据当前项目符号上下文——IBulletFormat.Type、.NumberedBulletStyle 和首个部分的 FontHeight——进行应用。非零的缩进偏移会应用于当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 调用此方法无论如何都会在以下情况抛出 **System.InvalidOperationException**：<br/>如果父格式对象不是段落（例如调用 ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() 将抛出异常）；<br/>或者段落未添加到任何 ITextFrame.Paragraphs 集合中（请先添加）； |

### 另见
* 类 [`IBulletFormat`](/slides/python-net/zh/aspose.slides/ibulletformat)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)