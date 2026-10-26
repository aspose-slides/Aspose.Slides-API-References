---
title: ToJpeg()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  출력 파일 이름이 \"myPath/myFilename.jpeg\"인 경우 결과는 \"myPath/myFilename_N.jpeg\" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.
type: docs
weight: 40
url: /ko/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) 메서드

입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  

출력 파일 이름이 "myPath/myFilename.jpeg"인 경우 결과는 "myPath/myFilename_N.jpeg" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션. |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) 메서드

입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  

출력 파일 이름이 "myPath/myFilename.jpeg"인 경우 결과는 "myPath/myFilename_N.jpeg" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션 |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | 생성된 각 이미지의 크기. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) 메서드

입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  

출력 파일 이름이 "myPath/myFilename.jpeg"인 경우 결과는 "myPath/myFilename_N.jpeg" 파일 집합으로 저장되며, 여기서 N은 슬라이드 번호입니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션. |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
| scale | **float** | 원본 슬라이드 크기에 비해 출력 이미지에 적용되는 스케일링 계수. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | 렌더링 옵션. |
## 비고

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)