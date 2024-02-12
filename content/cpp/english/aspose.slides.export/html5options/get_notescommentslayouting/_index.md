---
title: get_NotesCommentsLayouting()
second_title: Aspose.Slides for C++ API Reference
description: Provides options that control how notes and comments is placed in exported document. Read INotesCommentsLayoutingOptions.
type: docs
weight: 105
url: /aspose.slides.export/html5options/get_notescommentslayouting/
---
## Html5Options::get_NotesCommentsLayouting() method


Provides options that control how notes and comments is placed in exported document. Read [INotesCommentsLayoutingOptions](../../inotescommentslayoutingoptions/).

```cpp
System::SharedPtr<INotesCommentsLayoutingOptions> Aspose::Slides::Export::Html5Options::get_NotesCommentsLayouting() override
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
* Class [Html5Options](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)