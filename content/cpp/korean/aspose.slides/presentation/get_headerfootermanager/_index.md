---
title: get_HeaderFooterManager()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 실제 HeaderFooter 관리자를 반환합니다. 읽기 전용 IPresentationHeaderFooterManager.
type: docs
weight: 27
url: /ko/aspose.slides/presentation/get_headerfootermanager/
---
## Presentation::get_HeaderFooterManager() 메서드

실제 HeaderFooter 관리자를 반환합니다. 읽기 전용 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/).

```cpp
System::SharedPtr<IPresentationHeaderFooterManager> Aspose::Slides::Presentation::get_HeaderFooterManager() override
```

## 비고

다음 예제는 PowerPoint [Presentation](../)의 [Slide](../../slide/) 내부에서 바닥글 표시를 설정하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
auto slide = presentation->get_Slides()->idx_get(0);

System::SharedPtr<IBaseSlideHeaderFooterManager> headerFooterManager = slide->get_HeaderFooterManager();
// Property IsFooterVisible 은 슬라이드 바닥글 자리 표시자가 없음을 나타내는 데 사용됩니다.
if (!headerFooterManager->get_IsFooterVisible())
{
    // Method SetFooterVisibility 은 슬라이드 바닥글 자리 표시자를 보이게 하는 데 사용됩니다.
    headerFooterManager->SetFooterVisibility(true);
}

// Property IsSlideNumberVisible 은 슬라이드 페이지 번호 자리 표시자가 없음을 나타내는 데 사용됩니다.
if (!headerFooterManager->get_IsSlideNumberVisible())
{
    // Method SetSlideNumberVisibility 은 슬라이드 페이지 번호 자리 표시자를 보이게 하는 데 사용됩니다.
    headerFooterManager->SetSlideNumberVisibility(true);
}

// Property IsDateTimeVisible 은 슬라이드 날짜/시간 자리 표시자가 없음을 나타내는 데 사용됩니다.
if (!headerFooterManager->get_IsDateTimeVisible())
{
    // Method SetFooterVisibility 은 슬라이드 날짜/시간 자리 표시자를 보이게 하는 데 사용됩니다.
    headerFooterManager->SetDateTimeVisibility(true);
}

// Method SetFooterText 은 슬라이드 바닥글 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
headerFooterManager->SetFooterText(u"Footer text");
// Method SetDateTimeText 은 슬라이드 날짜/시간 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
headerFooterManager->SetDateTimeText(u"Date and time text");
presentation->Save(u"Presentation.ppt", SaveFormat::Ppt);
```
다음 예제는 [Slide](../../slide/) 내부에서 자식 바닥글 표시를 설정하는 방법을 보여줍니다.
```cpp
auto presentation = System::MakeObject<Presentation>(u"presentation.ppt");
System::SharedPtr<IMasterSlideHeaderFooterManager> headerFooterManager = presentation->get_Masters()->idx_get(0)->get_HeaderFooterManager();

// Method SetFooterAndChildFootersVisibility 은 마스터 슬라이드와 모든 자식 바닥글 자리 표시자를 보이게 하는 데 사용됩니다.
headerFooterManager->SetFooterAndChildFootersVisibility(true);

// Method SetSlideNumberAndChildSlideNumbersVisibility 은 마스터 슬라이드와 모든 자식 페이지 번호 자리 표시자를 보이게 하는 데 사용됩니다.
headerFooterManager->SetSlideNumberAndChildSlideNumbersVisibility(true);

// Method SetDateTimeAndChildDateTimesVisibility 은 마스터 슬라이드와 모든 자식 날짜/시간 자리 표시자를 보이게 하는 데 사용됩니다.
headerFooterManager->SetDateTimeAndChildDateTimesVisibility(true);

// Method SetFooterAndChildFootersText 은 마스터 슬라이드와 모든 자식 바닥글 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
headerFooterManager->SetFooterAndChildFootersText(u"Footer text");

// Method SetDateTimeAndChildDateTimesText 은 마스터 슬라이드와 모든 자식 날짜/시간 자리 표시자에 텍스트를 설정하는 데 사용됩니다.
headerFooterManager->SetDateTimeAndChildDateTimesText(u"Date and time text");
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPresentationHeaderFooterManager](../../ipresentationheaderfootermanager/)
* 클래스 [Presentation](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)