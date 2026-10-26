---
title: Camera class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/camera/
---
## Camera 클래스

Camera를 나타냅니다.

**상속:**[`Camera`](/slides/python-net/ko/aspose.slides/camera) → [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)

Camera 유형은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`camera_type`](/slides/python-net/ko/aspose.slides/camera/camera_type/) | Camera 유형.<br/>            읽기/쓰기 [`CameraPresetType`](/slides/python-net/ko/aspose.slides/camerapresettype). |
| [`field_of_view_angle`](/slides/python-net/ko/aspose.slides/camera/field_of_view_angle/) | Camera FOV (0-180도, 시야각).<br/>            읽기/쓰기 **float**. |
| [`zoom`](/slides/python-net/ko/aspose.slides/camera/zoom/) | Camera 줌 (백분율로 양수 값).<br/>            읽기/쓰기 **float**. |
| [`slide`](/slides/python-net/ko/aspose.slides/camera/slide/) |  |
| [`presentation`](/slides/python-net/ko/aspose.slides/camera/presentation/) |  |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`set_rotation(self, latitude, longitude, revolution)`](/slides/python-net/ko/aspose.slides/camera/set_rotation/#float-float-float) | 회전은 위도 좌표, 경도 좌표 및 축을 중심으로 한 회전을 사용하여 정의됩니다.<br/>            위도와 경도 좌표와 같이.<br/>            좌표 값 중 하나가 float.NaN이면, 모든 회전은 정의되지 않습니다. |
| [`get_rotation(self)`](/slides/python-net/ko/aspose.slides/camera/get_rotation/#) | 회전은 위도 좌표, 경도 좌표 및 축을 중심으로 한 회전을 사용하여 정의됩니다.<br/>            반환 배열의 첫 요소 - 위도, 두 번째 - 경도, 세 번째 - 회전.<br/>            회전이 정의되지 않은 경우 None을 반환합니다. |

### 참조
* 클래스 [`Camera`](/slides/python-net/ko/aspose.slides/camera)
* 클래스 [`PVIObject`](/slides/python-net/ko/aspose.slides/pviobject)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)