---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.export/pdfaccesspermissions/
---
## PdfAccessPermissions 열거형

문서가 사용자 접근으로 열릴 때 부여되어야 하는 접근 권한을 지정하는 플래그 집합을 포함합니다.

PdfAccessPermissions 형식은 다음 멤버를 노출합니다:

## 필드

| 필드 | 설명 |
| :- | :- |
| NONE | 사용자가 접근 권한이 없음을 지정합니다. |
| PRINT_DOCUMENT | 사용자가 문서를 인쇄할 수 있는지를 지정합니다(최고 품질 수준이 아닐 수도 있으며, 비트 [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) 가 또한 설정되어 있는지에 따라 달라집니다). |
| MODIFY_CONTENT | 사용자가 비트 [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT) 로 제어되는 작업 외의 작업을 통해 문서 내용을 수정할 수 있는지를 지정합니다. |
| COPY_TEXT_AND_GRAPHICS | 사용자가 비트 [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS) 로 제어되는 작업 이외의 작업을 통해 문서에서 텍스트와 그래픽을 복사하거나 추출할 수 있는지를 지정합니다. |
| ADD_OR_MODIFY_FIELDS | 사용자가 텍스트 주석을 추가하거나 수정하고, 대화형 양식 필드를 입력할 수 있는지를 지정합니다. 그리고 비트<br/>            [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) 가 또한 설정된 경우, 대화형 양식 필드(서명 필드 포함)를 생성하거나 수정할 수 있습니다.<br/>            |
| FILL_EXISTING_FIELDS | 비트 [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) 가 꺼져 있어도 사용자가 기존 대화형 양식 필드(서명 필드 포함)를 입력할 수 있는지를 지정합니다. |
| EXTRACT_TEXT_AND_GRAPHICS | 사용자가 장애가 있는 사용자를 위한 접근성 지원이나 기타 목적을 위해 텍스트와 그래픽을 추출할 수 있는지를 지정합니다. |
| ASSEMBLE_DOCUMENT | 비트 [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) 가 꺼져 있어도 사용자가 문서를 조합할 수 있는지를 지정합니다(페이지 삽입, 회전, 삭제 및 북마크 또는 썸네일 이미지 생성). |
| HIGH_QUALITY_PRINT | 사용자가 PDF 콘텐츠의 충실한 디지털 복사본을 생성할 수 있는 표현으로 문서를 인쇄할 수 있는지를 지정합니다. 이 비트가 꺼져 있고(비트 [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/ko/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) 가 설정된 경우) 인쇄는 외관의 저수준 표현으로 제한되며, 품질이 저하될 수 있습니다. |


### 참고
* 모듈 [`aspose.slides.export`](/slides/python-net/ko/aspose.slides.export)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)