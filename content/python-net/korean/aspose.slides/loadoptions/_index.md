---
title: LoadOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/loadoptions/
---
## LoadOptions 클래스

프레젠테이션을 로드할 때 추가 옵션(예: 형식 또는 기본 글꼴)을 지정할 수 있습니다.

LoadOptions 유형은 다음 멤버를 제공합니다:

## 생성자

| 생성자 | 설명 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides/loadoptions/__init__/#) | 새 기본 로드 옵션을 생성합니다. |
| [`__init__(self, load_format)`](/slides/python-net/ko/aspose.slides/loadoptions/__init__/#loadformat) | 새 로드 옵션을 생성합니다. |

## 속성

| 속성 | 설명 |
| :- | :- |
| [`load_format`](/slides/python-net/ko/aspose.slides/loadoptions/load_format/) | 로드할 프레젠테이션의 형식을 반환하거나 설정합니다.<br/>            읽기/쓰기 [`LoadFormat`](/slides/python-net/ko/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides/loadoptions/default_regular_font/) | 소스 글꼴을 찾을 수 없는 경우 사용할 일반 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`default_symbol_font`](/slides/python-net/ko/aspose.slides/loadoptions/default_symbol_font/) | 소스 글꼴을 찾을 수 없는 경우 사용할 기호 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`default_asian_font`](/slides/python-net/ko/aspose.slides/loadoptions/default_asian_font/) | 소스 글꼴을 찾을 수 없는 경우 사용할 아시아 글꼴을 반환하거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`password`](/slides/python-net/ko/aspose.slides/loadoptions/password/) | 비밀번호를 가져오거나 설정합니다.<br/>            읽기/쓰기 **str**. |
| [`only_load_document_properties`](/slides/python-net/ko/aspose.slides/loadoptions/only_load_document_properties/) | 이 속성은 프레젠테이션 파일이 비밀번호로 보호된 경우에 의미가 있습니다.<br/>            true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드되고 비밀번호는 무시되어야 함을 의미합니다.<br/>            false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드해야 함을 의미합니다.<br/>            프레젠테이션이 암호화되지 않은 경우 속성 값은 항상 무시됩니다.<br/>            암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다.<br/>            읽기/쓰기 **bool**. |
| [`warning_callback`](/slides/python-net/ko/aspose.slides/loadoptions/warning_callback/) | 경고를 수신하고 로드 <br/>            프로세스가 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ko/aspose.slides/loadoptions/blob_management_options/) | Binary Large Objects (BLOBs) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다,<br/>            예를 들어 임시 파일 사용 또는 메모리 내 최대 BLOB 바이트 수와 같습니다. 이러한 옵션은 특정 환경이나 요구 사항에 대한 최상의 성능/메모리 소비 비율을 설정하기 위한 것입니다.<br/>            Binary Large Object (BLOB)는 단일 엔터티로 저장된 바이너리 데이터이며, 즉 BLOB는 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다.<br/>            |
| [`document_level_font_sources`](/slides/python-net/ko/aspose.slides/loadoptions/document_level_font_sources/) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다.<br/>            이러한 글꼴은 프레젠테이션 전체 수명 동안 사용할 수 있으며 다른 프레젠테이션과 공유되지 않습니다 |
| [`interruption_token`](/slides/python-net/ko/aspose.slides/loadoptions/interruption_token/) | 중단 요청을 모니터링하기 위한 토큰.<br/>            <br/>            이 토큰은 전체 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 로드 또는 프레젠테이션 저장과 같은 장기 실행 작업은 [`InterruptionTokenSource.interrupt`](/slides/python-net/ko/aspose.slides/interruptiontokensource/interrupt) 메서드를 호출하여 [`InterruptionTokenSource`](/slides/python-net/ko/aspose.slides/interruptiontokensource)에 의해 중단됩니다. |
| [`resource_loading_callback`](/slides/python-net/ko/aspose.slides/loadoptions/resource_loading_callback/) | 외부 리소스 로딩을 관리하는 콜백 인터페이스를 반환하거나 설정합니다.<br/>            읽기/쓰기 [`IResourceLoadingCallback`](/slides/python-net/ko/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ko/aspose.slides/loadoptions/spreadsheet_options/) | 스프레드시트 옵션을 가져옵니다. 예를 들어, 이러한 옵션은 차트의 수식 계산에 영향을 줍니다. |
| [`default_text_language`](/slides/python-net/ko/aspose.slides/loadoptions/default_text_language/) | 프레젠테이션 텍스트의 기본 언어를 반환하거나 설정합니다.<br/>             읽기/쓰기 **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ko/aspose.slides/loadoptions/delete_embedded_binary_objects/) | 프레젠테이션 로드 중에 Aspose.Slides가 모든 내장 바이너리 객체를 삭제할지 여부를 결정합니다.<br/>            <br/>내장 바이너리 객체의 유형:<br/><br/><br/>* VBA 프로젝트 [`IPresentation.vba_project`](/slides/python-net/ko/aspose.slides/ipresentation/vba_project)<br/>* OLE 객체 내장 데이터 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX 컨트롤 바이너리 데이터 [`IControl.active_x_control_binary`](/slides/python-net/ko/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            읽기/쓰기 **bool**. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)