---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Aspose.Slides for C++ API Reference
description: "Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat::get(set)_Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values)."
type: docs
weight: 235
url: /aspose.slides/ibulletformat/applydefaultparagraphindentsshifts/
---
## IBulletFormat::ApplyDefaultParagraphIndentsShifts() method


Sets default non-zero shifts for effective paragraph Indent and MarginLeft when bullets is enabled (like PowerPoint do if enable paragraph bullets/numbering in it). If bullets is disabled then just reset paragraph Indent and MarginLeft (like PowerPoint do if disable paragraph bullets/numbering in it). Indents shifts are applied in regard to current bullet context - IBulletFormat::get(set)_Type, .NumberedBulletStyle and FontHeight of first portion. Non-zero indents shifts are applied to effective Indent and MarginLeft of current paragraph (make result values to be local values).

```cpp
virtual void Aspose::Slides::IBulletFormat::ApplyDefaultParagraphIndentsShifts()=0
```


### Exceptions

| Exception | Description |
| --- | --- |
| [System::InvalidOperationException](../../../system/invalidoperationexception/) | Calling this method doesn't matter and throw [System::InvalidOperationException](../../../system/invalidoperationexception/) in following cases: if parent formatted object is not a paragraph (for example calling ITextStyle-\>get_DefaultParagraphFormat()-\>get_Bullet()-\>[ApplyDefaultParagraphIndentsShifts()](./) will throw exception); or if paragraph wasn't added to any ITextFrame-\>get_Paragraphs() collection (add it first); |


## See Also

* Class [IBulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)