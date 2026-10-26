---
title: ToPng()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다. \"myPath/myFilename.png\"와 같이 출력 파일 이름을 지정하면 결과는 \"myPath/myFilename_N.png\" 파일 세트로 저장되며, 여기서 N은 슬라이드 번호입니다.
type: docs
weight: 53
url: /ko/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) method

입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다.

"myPath/myFilename.png"와 같이 출력 파일 이름을 지정하면 결과는 "myPath/myFilename_N.png" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션. |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method

입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다.

"myPath/myFilename.png"와 같이 출력 파일 이름을 지정하면 결과는 "myPath/myFilename_N.png" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 각 생성 이미지의 크기. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method

입력 프레젠테이션을 PNG 형식 이미지 세트로 변환합니다.

"myPath/myFilename.png"와 같이 출력 파일 이름을 지정하면 결과는 "myPath/myFilename_N.png" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션. |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
| scale | **float** | 원본 슬라이드 크기에 대비한 출력 이미지에 적용되는 배율 factor. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
## 비고

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [String](../../../system/string/)
* 클래스 [Convert](../)
* 클래스 [Size](../../../system.drawing/size/)
* 클래스 [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)