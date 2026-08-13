---
title: WriteAsEmf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드 내용을 EMF 파일로 저장합니다.
type: docs
weight: 170
url: /ko/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) 메서드


슬라이드 내용을 EMF 파일로 저장합니다.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 대상 스트림 |
## 비고



다음 코드 예제는 PowerPoint 프레젠테이션의 첫 번째 슬라이드를 메타파일로 변환하는 방법을 보여줍니다.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// 첫 번째 슬라이드를 메타파일로 저장합니다
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Stream](../../../system.io/stream/)
* 클래스 [Slide](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)