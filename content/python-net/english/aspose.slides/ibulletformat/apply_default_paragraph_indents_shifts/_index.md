---
title: apply_default_paragraph_indents_shifts method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docS
url: /aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 20
---


## apply_default_paragraph_indents_shifts {#}
Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


## Exceptions

| Exception | Description |
| :- | :- |
| .NET type System.InvalidOperationException | Calling this method doesn't matter and throw .NET type System.InvalidOperationException in following cases:<br/>            if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception);<br/>            or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |



