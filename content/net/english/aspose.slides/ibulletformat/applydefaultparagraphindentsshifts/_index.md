---
title: ApplyDefaultParagraphIndentsShifts
second_title: Aspose.Sildes for .NET API Reference
description: Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled like PowerPoint do if enable paragraph bullets/numbering in it. If bullets is disabled then just reset paragraph Indent and MarginLeft like PowerPoint do if disable paragraph bullets/numbering in it. Indents shifts are applied in regard to current bullet context - IBulletFormat.Type .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph make result values to be local values.
type: docs
weight: 110
url: /aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---

## IBulletFormat.ApplyDefaultParagraphIndentsShifts method

Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).

```csharp
public void ApplyDefaultParagraphIndentsShifts()
```

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Calling this method doesn't matter and throw InvalidOperationException in following cases: if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception); or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |

### See Also

* interface [IBulletFormat](../../ibulletformat)
* namespace [Aspose.Slides](../../ibulletformat)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
