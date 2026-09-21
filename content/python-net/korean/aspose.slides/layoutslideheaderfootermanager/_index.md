---
title: LayoutSlideHeaderFooterManager class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/layoutslideheaderfootermanager/
---
## LayoutSlideHeaderFooterManager 클래스

Represents manager which holds behavior of the layout slide footer, date-time, page number placeholders and all child placeholders.
            Child placeholders mean placeholders are contained on depending slides.
            Depending slides use and depend on layout slide.

**상속:**[`LayoutSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseheaderfootermanager)

The LayoutSlideHeaderFooterManager type exposes the following members:

## 속성

| Property | Description |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/is_footer_visible/) | footer 자리표시자가 존재함을 나타내는 값을 가져옵니다.<br/>            읽기 **bool**. |
| [`is_slide_number_visible`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/is_slide_number_visible/) | 페이지 번호 자리표시자가 존재함을 나타내는 값을 가져옵니다.<br/>            읽기**bool**. |
| [`is_date_time_visible`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/is_date_time_visible/) | 날짜-시간 자리표시자가 존재함을 나타내는 값을 가져옵니다.<br/>            읽기**bool**. |

## 메서드

| Method | Description |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_footer_visibility/#bool) | 슬라이드 footer 자리표시자의 가시성을 변경합니다. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_slide_number_visibility/#bool) | 슬라이드 페이지 번호 자리표시자의 가시성을 변경합니다. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_date_time_visibility/#bool) | 슬라이드 날짜-시간 자리표시자의 가시성을 변경합니다. |
| [`set_footer_text(self, text)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_footer_text/#str) | 슬라이드 footer 자리표시자에 텍스트를 설정합니다. |
| [`set_date_time_text(self, text)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_date_time_text/#str) | 슬라이드 날짜-시간 자리표시자에 텍스트를 설정합니다. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | 레이아웃 슬라이드 footer 자리표시자와 모든 자식 footer 자리표시자의 가시성을 변경합니다.<br/>            자식 자리표시자는 종속 슬라이드에 포함된 자리표시자를 의미합니다.<br/>            종속 슬라이드는 마스터 슬라이드를 사용하고 의존합니다. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | 레이아웃 슬라이드 페이지 번호 자리표시자와 모든 자식 페이지 번호 자리표시자의 가시성을 변경합니다.<br/>            자식 자리표시자는 종속 슬라이드에 포함된 자리표시자를 의미합니다.<br/>            종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | 레이아웃 슬라이드 날짜-시간 자리표시자와 모든 자식 날짜-시간 자리표시자의 가시성을 변경합니다.<br/>            자식 자리표시자는 종속 슬라이드에 포함된 자리표시자를 의미합니다.<br/>            종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_footer_and_child_footers_text/#str) | 레이아웃 슬라이드 footer 자리표시자와 모든 자식 footer 자리표시자에 텍스트를 설정합니다.<br/>            자식 자리표시자는 종속 슬라이드에 포함된 자리표시자를 의미합니다.<br/>            종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | 레이아웃 슬라이드 날짜-시간 자리표시자와 모든 자식 날짜-시간 자리표시자에 텍스트를 설정합니다.<br/>            자식 자리표시자는 종속 슬라이드에 포함된 자리표시자를 의미합니다.<br/>            종속 슬라이드는 레이아웃 슬라이드를 사용하고 의존합니다. |


### 참조
* 클래스 [`BaseHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseheaderfootermanager)
* 클래스 [`BaseSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseslideheaderfootermanager)
* 클래스 [`LayoutSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/layoutslideheaderfootermanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)