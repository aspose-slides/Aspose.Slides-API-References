---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API Reference
description: Splits the text content of the ITextFrame into an array of strings,  where each element corresponds to a separate text column within the frame.
type: docs
weight: 144
url: /aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() method


Splits the text content of the [ITextFrame](../../itextframe/) into an array of strings, 

 where each element corresponds to a separate text column within the frame.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```


### Return Value

An array of strings, where each string represents the text content of a specific column 

 in the [ITextFrame](../../itextframe/).
## Remarks



If the text frame does not contain multiple columns, the returned array will have a single element 

 containing the full text. 

 Empty columns will be represented as empty strings in the array. 

The following example demonstrates how to use [TextFrame::SplitTextByColumns](./): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// Get the first shape on the slide and cast it to ITextFrame
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// Split the text frame content into columns
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// Print each column's text to the console
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)