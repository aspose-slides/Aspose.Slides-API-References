---
title: ToTiff()
second_title: Aspose.Slides for C++ API 참조
description: 입력 프레젠테이션을 TIFF 형식 이미지 집합으로 변환합니다. 출력 파일 이름을 \"myPath/myFilename.tiff\" 로 지정하면 결과가 \"myPath/myFilename_N.tiff\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다.
type: docs
weight: 66
url: /ko/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) 메서드

입력 프레젠테이션을 TIFF 형식 이미지 집합으로 변환합니다.  

출력 파일 이름을 "myPath/myFilename.tiff" 로 지정하면 결과가 "myPath/myFilename_N.tiff" 파일 집합으로 저장되며, N은 슬라이드 번호를 나타냅니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션. |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) 메서드

입력 프레젠테이션을 사용자 지정 옵션으로 TIFF 형식으로 변환합니다.  
출력 파일 이름을 "myPath/myFilename.tiff" 로 지정하고 *multipage* 가 **false** 인 경우, 결과는 "myPath/myFilename_N.tiff" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. 반대로 *multipage* 가 **true** 인 경우, 결과는 다중 페이지 "myPath/myFilename.tiff" 문서가 됩니다.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | 입력 프레젠테이션. |
| outputFileName | [System::String](../../../system/string/) | 출력 파일 이름. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | TIFF 저장 옵션. |
| multipage | **bool** | 생성된 TIFF 문서가 다중 페이지여야 하는지 여부를 지정합니다. |

## 비고

```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Presentation](../../../aspose.slides/presentation/)
* 클래스 [String](../../../system/string/)
* 클래스 [Convert](../)
* 클래스 [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* 네임스페이스 [Aspose::Slides::LowCode](../../)
* 라이브러리 [Aspose.Slides](../../../)