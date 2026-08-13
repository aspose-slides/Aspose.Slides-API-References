---
title: Convert
second_title: Aspose.Slides for C++ API 레퍼런스
description: Presentation을 변환하기 위한 메서드 그룹을 나타냅니다.
type: docs
weight: 27
url: /ko/aspose.slides.lowcode/convert/
---
## 변환 클래스

[Presentation](../../aspose.slides/presentation/)를 변환하기 위한 메서드 그룹을 나타냅니다.

```cpp
class Convert
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | 전달된 출력 경로 확장자를 사용하여 필요한 내보내기 형식을 결정하면서 [Presentation](../../aspose.slides/presentation/)를 변환합니다. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.jpeg\"인 경우, 결과는 \"myPath/myFilename_N.jpeg\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.jpeg\"인 경우, 결과는 \"myPath/myFilename_N.jpeg\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.jpeg\"인 경우, 결과는 \"myPath/myFilename_N.jpeg\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)를 PDF로 변환합니다. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/)를 PDF로 변환합니다. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)를 PDF로 변환합니다. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | [Presentation](../../aspose.slides/presentation/)를 PDF로 변환합니다. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 입력 프레젠테이션을 PNG 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.png\"인 경우, 결과는 \"myPath/myFilename_N.png\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | 입력 프레젠테이션을 PNG 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.png\"인 경우, 결과는 \"myPath/myFilename_N.png\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | 입력 프레젠테이션을 PNG 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.png\"인 경우, 결과는 \"myPath/myFilename_N.png\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | [Presentation](../../aspose.slides/presentation/)를 SVG로 변환합니다. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/)를 SVG로 변환합니다. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | [Presentation](../../aspose.slides/presentation/)를 SVG로 변환합니다. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/)를 SVG로 변환합니다. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Presentation](../../aspose.slides/presentation/)를 SVG로 변환합니다. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | 입력 프레젠테이션을 TIFF 형식 이미지 집합으로 변환합니다.

 출력 파일 이름이 \"myPath/myFilename.tiff\"인 경우, 결과는 \"myPath/myFilename_N.tiff\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | 입력 프레젠테이션을 사용자 지정 옵션으로 TIFF 형식으로 변환합니다. 출력 파일 이름이 \"myPath/myFilename.tiff\"이고 *multipage*가 **false**인 경우, 결과는 \"myPath/myFilename_N.tiff\" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. 반대로 *multipage*가 **true**인 경우, 결과는 다중 페이지 \"myPath/myFilename.tiff\" 문서가 됩니다. |

## 타입 정의

| 타입 정의 | 설명 |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | 각 [Slide](../../aspose.slides/slide/)에 대해 호출되는 콜백이며, 반환될 출력 경로가 예상됩니다. |

## 비고



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## 참고

* 네임스페이스 [Aspose::Slides::LowCode](../)
* 라이브러리 [Aspose.Slides](../../)