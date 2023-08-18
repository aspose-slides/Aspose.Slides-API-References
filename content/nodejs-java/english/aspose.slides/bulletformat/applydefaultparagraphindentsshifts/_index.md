---
title: applyDefaultParagraphIndentsShifts
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---

## applyDefaultParagraphIndentsShifts()  function

 Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat.Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).
 

### Error

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Calling this function doesn't matter and throw InvalidOperationException in following cases: if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception); or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |


---


