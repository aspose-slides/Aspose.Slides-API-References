---
title: SplitTextByColumns()
second_title: Aspose.Slides for C++ API 참조
description: ITextFrame의 텍스트 내용을 문자열 배열로 분할하며, 각 요소는 프레임 내의 개별 텍스트 열에 해당합니다.
type: docs
weight: 118
url: /ko/aspose.slides/itextframe/splittextbycolumns/
---
## ITextFrame::SplitTextByColumns() 메서드

[ITextFrame](../)의 텍스트 내용을 문자열 배열로 분할하고,  
각 요소는 프레임 내의 개별 텍스트 열에 해당합니다.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::ITextFrame::SplitTextByColumns()=0
```

### 반환 값

문자열 배열이며, 각 문자열은 특정 열의 텍스트 내용을 나타내며  
[ITextFrame](../)에 있습니다.

## 비고

텍스트 프레임에 여러 열이 포함되어 있지 않으면, 반환된 배열은 단일 요소를  

전체 텍스트를 포함합니다.

빈 열은 배열에서 빈 문자열로 표시됩니다.

다음 예제는 [ITextFrame::SplitTextByColumns](./) 사용 방법을 보여줍니다:  
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"example.pptx");

// 슬라이드에서 첫 번째 도형을 가져와 ITextFrame으로 캐스팅합니다
System::SharedPtr<ITextFrame> textFrame = System::AsCast<ITextFrame>(pres->get_Slide(0)->get_Shape(0));
// 텍스트 프레임 내용을 열로 분할합니다
System::ArrayPtr<System::String> columnsText = textFrame->SplitTextByColumns();
// 각 열의 텍스트를 콘솔에 출력합니다
for (System::String column : columnsText)
{
    System::Console::WriteLine(column);
}
```

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [ITextFrame](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)