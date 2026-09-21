---
title: MasterSlideHeaderFooterManager class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/masterslideheaderfootermanager/
---
## MasterSlideHeaderFooterManager 클래스

마스터 슬라이드 푸터, 날짜-시간, 페이지 번호 자리 표시자 및 모든 하위 자리 표시자의 동작을 보유하는 관리자를 나타냅니다.
            하위 자리 표시자는 해당 레이아웃 슬라이드와 종속 슬라이드에 포함된 자리 표시자를 의미합니다.
            해당 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 종속됩니다.

**상속:**[`MasterSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseheaderfootermanager)

MasterSlideHeaderFooterManager 형식은 다음 멤버를 노출합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/is_footer_visible/) | 푸터 자리 표시자가 존재함을 나타내는 값을 가져옵니다.<br/>            읽기 **bool**. |
| [`is_slide_number_visible`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/is_slide_number_visible/) | 페이지 번호 자리 표시자가 존재함을 나타내는 값을 가져옵니다.<br/>            읽기**bool**. |
| [`is_date_time_visible`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/is_date_time_visible/) | 날짜-시간 자리 표시자가 존재함을 나타내는 값을 가져옵니다.<br/>            읽기**bool**. |

## 메서드

| 메서드 | 설명 |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_footer_visibility/#bool) | 슬라이드 푸터 자리 표시자의 가시성을 변경합니다. |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_slide_number_visibility/#bool) | 슬라이드 페이지 번호 자리 표시자의 가시성을 변경합니다. |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_date_time_visibility/#bool) | 슬라이드 날짜-시간 자리 표시자의 가시성을 변경합니다. |
| [`set_footer_text(self, text)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_footer_text/#str) | 슬라이드 푸터 자리 표시자에 텍스트를 설정합니다. |
| [`set_date_time_text(self, text)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_date_time_text/#str) | 슬라이드 날짜-시간 자리 표시자에 텍스트를 설정합니다. |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | 마스터 슬라이드 푸터 자리 표시자와 모든 하위 푸터 자리 표시자의 가시성을 변경합니다.<br/>            하위 자리 표시자는 해당 레이아웃 슬라이드와 종속 슬라이드에 포함된 자리 표시자를 의미합니다.<br/>            해당 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 종속됩니다. |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | 마스터 슬라이드 페이지 번호 자리 표시자와 모든 하위 페이지 번호 자리 표시자의 가시성을 변경합니다.<br/>            하위 자리 표시자는 해당 레이아웃 슬라이드와 종속 슬라이드에 포함된 자리 표시자를 의미합니다.<br/>            해당 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 종속됩니다. |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | 마스터 슬라이드 날짜-시간 자리 표시자와 모든 하위 날짜-시간 자리 표시자의 가시성을 변경합니다.<br/>            하위 자리 표시자는 해당 레이아웃 슬라이드와 종속 슬라이드에 포함된 자리 표시자를 의미합니다.<br/>            해당 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 종속됩니다. |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_footer_and_child_footers_text/#str) | 마스터 슬라이드 푸터 자리 표시자와 모든 하위 푸터 자리 표시자에 텍스트를 설정합니다.<br/>            하위 자리 표시자는 해당 레이아웃 슬라이드와 종속 슬라이드에 포함된 자리 표시자를 의미합니다.<br/>            해당 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 종속됩니다. |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | 마스터 슬라이드 날짜-시간 자리 표시자와 모든 하위 날짜-시간 자리 표시자에 텍스트를 설정합니다.<br/>            하위 자리 표시자는 해당 레이아웃 슬라이드와 종속 슬라이드에 포함된 자리 표시자를 의미합니다.<br/>            해당 레이아웃 슬라이드와 슬라이드는 마스터 슬라이드를 사용하고 종속됩니다. |

### 참고
* 클래스 [`BaseHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseheaderfootermanager)
* 클래스 [`BaseSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/baseslideheaderfootermanager)
* 클래스 [`MasterSlideHeaderFooterManager`](/slides/python-net/ko/aspose.slides/masterslideheaderfootermanager)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)