---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API Reference
description: Splits the text content of the ITextFrame into an array of strings,  where each element corresponds to a separate text column within the frame.
type: docs
weight: 118
url: /aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() method


Splits the text content of the [ITextFrame](../) into an array of strings, 

 where each element corresponds to a separate text column within the frame.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```


### Return Value

An array of strings, where each string represents the text content of a specific column 

 in the [ITextFrame](../).
## Remarks



If the text frame does not contain multiple columns, the returned array will have a single element 

 containing the full text. 

 Empty columns will be represented as empty strings in the array. 

The following example demonstrates how to use [ITextFrame::SplitTextByColumns](./): 
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
* Class [ITextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)