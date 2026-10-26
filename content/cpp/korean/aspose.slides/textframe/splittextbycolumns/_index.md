---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API 레퍼런스
description: ITextFrame의 텍스트 내용을 문자열 배열로 분할하며, 각 요소는 프레임 내의 별도 텍스트 열에 해당합니다.
type: docs
weight: 144
url: /ko/aspose.slides/textframe/splittextbycolumns/
---
## TextFrame::SplitTextByColumns() 메서드

Splits the text content of the [ITextFrame](../../itextframe/) into an array of strings, 
where each element corresponds to a separate text column within the frame.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::TextFrame::SplitTextByColumns() override
```

### 반환값

An array of strings, where each string represents the text content of a specific column 
in the [ITextFrame](../../itextframe/).

## 비고

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

## 관련 항목

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [TextFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)