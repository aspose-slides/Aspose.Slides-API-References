---
title: GeometryPath class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/geometrypath/
---
## GeometryPath 클래스

GeometryShape의 기하학 경로를 나타냅니다.

GeometryPath 형식은 다음 멤버를 노출합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides/geometrypath/__init__/#) | GeometryPath의 인스턴스를 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`path_data`](/slides/python-net/ko/aspose.slides/geometrypath/path_data/) | GeometryShape의 geometry path를 경로 세그먼트 배열로 반환합니다. |
| [`fill_mode`](/slides/python-net/ko/aspose.slides/geometrypath/fill_mode/) | 채우기 모드를 설정합니다. |
| [`stroke`](/slides/python-net/ko/aspose.slides/geometrypath/stroke/) | 스트로크 모양을 설정합니다. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`line_to(self, point)`](/slides/python-net/ko/aspose.slides/geometrypath/line_to/#asposepydrawingpointf) | 경로 끝에 선을 추가합니다. |
| [`line_to(self, x, y)`](/slides/python-net/ko/aspose.slides/geometrypath/line_to/#float-float) | 경로 끝에 선을 추가합니다. |
| [`line_to(self, point, index)`](/slides/python-net/ko/aspose.slides/geometrypath/line_to/#asposepydrawingpointf-int) | 경로의 지정된 위치에 선을 추가합니다. |
| [`line_to(self, x, y, index)`](/slides/python-net/ko/aspose.slides/geometrypath/line_to/#float-float-int) | 경로의 지정된 위치에 선을 추가합니다. |
| [`cubic_bezier_to(self, point1, point2, point3)`](/slides/python-net/ko/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf) | 경로 끝에 큐빅 베지어 곡선을 추가합니다. |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3)`](/slides/python-net/ko/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float) | 경로 끝에 큐빅 베지어 곡선을 추가합니다. |
| [`cubic_bezier_to(self, point1, point2, point3, index)`](/slides/python-net/ko/aspose.slides/geometrypath/cubic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-asposepydrawingpointf-int) | 경로의 지정된 위치에 큐빅 베지어 곡선을 추가합니다. |
| [`cubic_bezier_to(self, x1, y1, x2, y2, x3, y3, index)`](/slides/python-net/ko/aspose.slides/geometrypath/cubic_bezier_to/#float-float-float-float-float-float-int) | 경로의 지정된 위치에 큐빅 베지어 곡선을 추가합니다. |
| [`quadratic_bezier_to(self, point1, point2)`](/slides/python-net/ko/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf) | 경로 끝에 2차 베지어 곡선을 추가합니다. |
| [`quadratic_bezier_to(self, x1, y1, x2, y2)`](/slides/python-net/ko/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float) | 경로 끝에 2차 베지어 곡선을 추가합니다. |
| [`quadratic_bezier_to(self, point1, point2, index)`](/slides/python-net/ko/aspose.slides/geometrypath/quadratic_bezier_to/#asposepydrawingpointf-asposepydrawingpointf-int) | 경로의 지정된 위치에 2차 베지어 곡선을 추가합니다. |
| [`quadratic_bezier_to(self, x1, y1, x2, y2, index)`](/slides/python-net/ko/aspose.slides/geometrypath/quadratic_bezier_to/#float-float-float-float-int) | 경로의 지정된 위치에 2차 베지어 곡선을 추가합니다. |
| [`move_to(self, point)`](/slides/python-net/ko/aspose.slides/geometrypath/move_to/#asposepydrawingpointf) | 다음 점 위치를 설정합니다. |
| [`move_to(self, x, y)`](/slides/python-net/ko/aspose.slides/geometrypath/move_to/#float-float) | 다음 점 위치를 설정합니다. |
| [`remove_at(self, index)`](/slides/python-net/ko/aspose.slides/geometrypath/remove_at/#int) | geometry path의 지정된 인덱스에 있는 세그먼트를 제거합니다. |
| [`close_figure(self)`](/slides/python-net/ko/aspose.slides/geometrypath/close_figure/#) | 이 경로의 현재 도형을 닫습니다. |
| [`arc_to(self, width, heigth, start_angle, sweep_angle)`](/slides/python-net/ko/aspose.slides/geometrypath/arc_to/#float-float-float-float) | 지정된 호를 경로에 추가합니다. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)