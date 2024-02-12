---
title: set_NotesCommentsLayouting()
second_title: Aspose.Slides for C++ API Reference
description: Provides options that control how notes and comments is placed in exported document. Write INotesCommentsLayoutingOptions.
type: docs
weight: 118
url: /aspose.slides.export/ihtml5options/set_notescommentslayouting/
---
## IHtml5Options::set_NotesCommentsLayouting(System::SharedPtr\<INotesCommentsLayoutingOptions\>) method


Provides options that control how notes and comments is placed in exported document. Write [INotesCommentsLayoutingOptions](../../inotescommentslayoutingoptions/).

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_NotesCommentsLayouting(System::SharedPtr<INotesCommentsLayoutingOptions> value)=0
```

## Remarks


Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"test.pptx");

System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayoutingOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
notesCommentsLayoutingOptions->set_NotesPosition(Aspose::Slides::Export::NotesPositions::BottomTruncated);

System::SharedPtr<Html5Options> html5Options = System::MakeObject<Html5Options>();
html5Options->set_OutputPath(u"test_pptx");
html5Options->set_NotesCommentsLayouting(notesCommentsLayoutingOptions);

pres->Save(u"index.html", Aspose::Slides::Export::SaveFormat::Html5, html5Options);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [INotesCommentsLayoutingOptions](../../inotescommentslayoutingoptions/)
* Class [IHtml5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)