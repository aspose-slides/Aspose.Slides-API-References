---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
在启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时的行为），为有效的段落 Indent 和 MarginLeft 设置默认的非零偏移。如果禁用项目符号，则仅重置段落 Indent 和 MarginLeft（如 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移基于当前项目符号上下文 - IBulletFormat.Type、.NumberedBulletStyle 和首个部分的 FontHeight 应用。非零缩进偏移被应用到当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 在以下情况调用此方法会抛出 **System.InvalidOperationException**：<br/>            如果父格式化对象不是段落（例如调用 ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() 会抛出异常）；<br/>            或者段落未被添加到任何 ITextFrame.Paragraphs 集合中（请先添加）； |

### 另请参见
* 类 [`BulletFormat`](/slides/python-net/zh/aspose.slides/bulletformat)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)