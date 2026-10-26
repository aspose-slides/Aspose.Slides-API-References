---
title: PPImage class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/ppimage/
---
## PPImage 클래스

프레젠테이션에서 이미지를 나타냅니다.

PPImage 형식은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`binary_data`](/slides/python-net/ko/aspose.slides/ppimage/binary_data/) | 이미지 데이터의 사본을 반환합니다.<br/>            읽기 전용 **int**[]. |
| [`image`](/slides/python-net/ko/aspose.slides/ppimage/image/) | 이미지의 사본을 반환합니다.<br/>            읽기 전용 [`IImage`](/slides/python-net/ko/aspose.slides/iimage). |
| [`svg_image`](/slides/python-net/ko/aspose.slides/ppimage/svg_image/) | ISvgImage 객체 [`ISvgImage`](/slides/python-net/ko/aspose.slides/isvgimage)를 반환하거나 설정합니다 |
| [`content_type`](/slides/python-net/ko/aspose.slides/ppimage/content_type/) | 이미지의 MIME 유형을 [`PPImage.binary_data`](/slides/python-net/ko/aspose.slides/ppimage/binary_data)로 인코딩하여 반환합니다.<br/>            읽기 전용 **str**. |
| [`width`](/slides/python-net/ko/aspose.slides/ppimage/width/) | 이미지의 너비를 반환합니다.<br/>            읽기 전용 **int**. |
| [`height`](/slides/python-net/ko/aspose.slides/ppimage/height/) | 이미지의 높이를 반환합니다.<br/>            읽기 전용 **int**. |
| [`x`](/slides/python-net/ko/aspose.slides/ppimage/x/) | 이미지의 X 오프셋을 반환합니다.<br/>            읽기 전용 **int**. |
| [`y`](/slides/python-net/ko/aspose.slides/ppimage/y/) | 이미지의 Y 오프셋을 반환합니다.<br/>            읽기 전용 **int**. |

## 메서드

| Method | Description |
| :- | :- |
| [`replace_image(self, new_image_data)`](/slides/python-net/ko/aspose.slides/ppimage/replace_image/#bytes) | 이미지 데이터를 교체합니다.<br/>            새로운 이미지 데이터. newImageData 매개변수가 None인 경우. |
| [`replace_image(self, new_image)`](/slides/python-net/ko/aspose.slides/ppimage/replace_image/#iimage) | 이미지 데이터를 교체합니다. 주의: 이미지가 메타파일인 경우 래스터화됩니다. 대신 ReplaceImage(byte[])를 사용하십시오.<br/>            새로운 이미지. newImage 매개변수가 None인 경우. |
| [`replace_image(self, new_image)`](/slides/python-net/ko/aspose.slides/ppimage/replace_image/#ippimage) | 이미지 데이터를 교체합니다.<br/>            새로운 IPPImage. newImage 매개변수가 None인 경우. |


### 관련 항목
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)