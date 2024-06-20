---
title: ReplaceText()
second_title: Aspose.Slides for C++ API Reference
description: Replaces all occurrences of the specified text with another specified text.
type: docs
weight: 131
url: /aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) method


Replaces all occurrences of the specified text with another specified text.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | The string to be replaced. |
| newText | [System::String](../../../system/string/) | The string to replace all occurrences of oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Text search options [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Callback object for saving replacement operation result [IFindResultCallback](../../ifindresultcallback/). |
## Remarks



The following sample code shows how to replace one speified string with another speified string. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Replace all separate 'the' occurrences with '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ITextSearchOptions](../../itextsearchoptions/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)