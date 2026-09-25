---
title: Convert class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.lowcode/convert/
---
## Convert 클래스

[`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 변환하기 위해 설계된 메서드 그룹을 나타냅니다.

Convert 타입은 다음 멤버를 공개합니다:

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`to_pdf(pres_path, out_path)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_pdf/#str-str) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 PDF로 변환합니다. |
| [`to_pdf(pres_path, out_path, options)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_pdf/#str-str-asposeslidesexportipdfoptions) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 PDF로 변환합니다. |
| [`to_pdf(pres, out_path)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_pdf/#presentation-str) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 PDF로 변환합니다. |
| [`to_pdf(pres, out_path, options)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_pdf/#presentation-str-asposeslidesexportipdfoptions) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 PDF로 변환합니다. |
| [`to_svg(pres_path)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_svg/#str) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 SVG로 변환합니다. |
| [`to_svg(pres, options)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_svg/#presentation-asposeslidesexportisvgoptions) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)을 SVG로 변환합니다. |
| [`to_jpeg(pres, output_file_name)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_jpeg/#presentation-str) | 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.jpeg"인 경우, 결과는 "myPath/myFilename_N.jpeg" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_jpeg(pres, output_file_name, image_size)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-asposeslidessize) | 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.jpeg"인 경우, 결과는 "myPath/myFilename_N.jpeg" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_jpeg(pres, output_file_name, scale, options)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_jpeg/#presentation-str-float-asposeslidesexportirenderingoptions) | 입력 프레젠테이션을 JPEG 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.jpeg"인 경우, 결과는 "myPath/myFilename_N.jpeg" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_png(pres, output_file_name)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_png/#presentation-str) | 입력 프레젠테이션을 PNG 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.png"인 경우, 결과는 "myPath/myFilename_N.png" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_png(pres, output_file_name, image_size)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_png/#presentation-str-asposeslidessize) | 입력 프레젠테이션을 PNG 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.png"인 경우, 결과는 "myPath/myFilename_N.png" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_png(pres, output_file_name, scale, options)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_png/#presentation-str-float-asposeslidesexportirenderingoptions) | 입력 프레젠테이션을 PNG 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.png"인 경우, 결과는 "myPath/myFilename_N.png" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_tiff(pres, output_file_name)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_tiff/#presentation-str) | 입력 프레젠테이션을 TIFF 형식 이미지 집합으로 변환합니다.  <br/>            출력 파일 이름이 "myPath/myFilename.tiff"인 경우, 결과는 "myPath/myFilename_N.tiff" 파일 집합으로 저장되며, N은 슬라이드 번호입니다. |
| [`to_tiff(pres, output_file_name, options, multipage)`](/slides/python-net/ko/aspose.slides.lowcode/convert/to_tiff/#presentation-str-asposeslidesexportitiffoptions-bool) | 입력 프레젠테이션을 사용자 지정 옵션으로 TIFF 형식으로 변환합니다.<br/>            출력 파일 이름이 "myPath/myFilename.tiff"이고 `multipage`가 `false`인 경우, 결과는 "myPath/myFilename_N.tiff" 파일 집합으로 저장됩니다. N은 슬라이드 번호입니다.<br/>            반면 `multipage`가 `true`이면, 결과는 다중 페이지 "myPath/myFilename.tiff" 문서가 됩니다. |
| [`auto_by_extension(pres_path, out_path)`](/slides/python-net/ko/aspose.slides.lowcode/convert/auto_by_extension/#str-str) | [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)를 전달된 출력 경로 확장자를 사용하여 필요한 내보내기 형식으로 변환합니다. |

### 참조
* 클래스 [`Presentation`](/slides/python-net/ko/aspose.slides/presentation)
* 모듈 [`aspose.slides.lowcode`](/slides/python-net/ko/aspose.slides.lowcode)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)