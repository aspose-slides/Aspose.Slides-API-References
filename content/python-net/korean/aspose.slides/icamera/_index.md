---
title: ICamera class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/icamera/
---
## ICamera 클래스

카메라를 나타냅니다.

ICamera 타입은 다음 멤버를 제공합니다:

## 속성

| Property | Description |
| :- | :- |
| [`camera_type`](/slides/python-net/ko/aspose.slides/icamera/camera_type/) | Camera type<br/>            읽기/쓰기 [`CameraPresetType`](/slides/python-net/ko/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ko/aspose.slides/icamera/field_of_view_angle/) | Camera FOV (0-180 deg, field of View)<br/>            읽기/쓰기 **float**. |
| [`zoom`](/slides/python-net/ko/aspose.slides/icamera/zoom/) | Camera zoom (positive value in percentage)<br/>            읽기/쓰기 **float**. |

## 메서드

| Method | Description |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ko/aspose.slides/icamera/set_rotation/#float-float-float) | 위도와 경도 좌표 및 축을 중심으로 회전을 정의합니다.<br/>            좌표값 중 하나가 float.NaN인 경우, 모든 회전은 정의되지 않습니다. |
| [`get_rotation(self)`](/slides/python-net/ko/aspose.slides/icamera/get_rotation/#) | 위도와 경도 좌표 및 축을 중심으로 회전을 정의합니다.<br/>            반환 배열의 첫 번째 요소는 위도, 두 번째 요소는 경도, 세 번째 요소는 회전입니다.<br/>            회전이 정의되지 않은 경우 None을 반환합니다. |


### 참고
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)