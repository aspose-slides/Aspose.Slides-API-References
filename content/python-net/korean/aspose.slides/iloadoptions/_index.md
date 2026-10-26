---
title: ILoadOptions class
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iloadoptions/
---
## ILoadOptions 클래스

프레젠테이션을 로드할 때 추가 옵션(예: 형식 또는 기본 글꼴)을 지정할 수 있습니다.

ILoadOptions 형식은 다음 멤버를 제공합니다:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`load_format`](/slides/python-net/ko/aspose.slides/iloadoptions/load_format/) | 로드할 프레젠테이션의 형식을 반환하거나 설정합니다.<br/>            Read/write [`LoadFormat`](/slides/python-net/ko/aspose.slides/loadformat). |
| [`default_regular_font`](/slides/python-net/ko/aspose.slides/iloadoptions/default_regular_font/) | 원본 글꼴을 찾을 수 없을 경우 사용되는 기본 글꼴을 반환하거나 설정합니다.<br/>            Read-write **str**. |
| [`default_symbol_font`](/slides/python-net/ko/aspose.slides/iloadoptions/default_symbol_font/) | 원본 글꼴을 찾을 수 없을 경우 사용되는 심볼 글꼴을 반환하거나 설정합니다.<br/>            Read-write **str**. |
| [`default_asian_font`](/slides/python-net/ko/aspose.slides/iloadoptions/default_asian_font/) | 원본 글꼴을 찾을 수 없을 경우 사용되는 아시아 글꼴을 반환하거나 설정합니다.<br/>            Read-write **str**. |
| [`password`](/slides/python-net/ko/aspose.slides/iloadoptions/password/) | 비밀번호를 가져오거나 설정합니다.<br/>            Read-write **str**. |
| [`only_load_document_properties`](/slides/python-net/ko/aspose.slides/iloadoptions/only_load_document_properties/) | 프레젠테이션 파일이 비밀번호로 보호된 경우에만 이 속성이 의미가 있습니다.<br/>            true 값은 암호화된 프레젠테이션 파일에서 문서 속성만 로드하고 비밀번호는 무시해야 함을 의미합니다.<br/>            false 값은 올바른 비밀번호를 사용하여 전체 암호화된 프레젠테이션을 로드해야 함을 의미합니다.<br/>            프레젠테이션이 암호화되지 않은 경우 이 속성 값은 항상 무시됩니다.<br/>            암호화된 파일의 문서 속성이 공개되지 않았고 속성 값이 true인 경우 문서 속성을 로드할 수 없으며 예외가 발생합니다.<br/>            Read-write **bool**. |
| [`warning_callback`](/slides/python-net/ko/aspose.slides/iloadoptions/warning_callback/) | 경고를 수신하고 로드 과정이 계속될지 중단될지를 결정하는 객체를 반환하거나 설정합니다.<br/>            Read/write [`IWarningCallback`](/slides/python-net/ko/aspose.slides.warnings/iwarningcallback). |
| [`blob_management_options`](/slides/python-net/ko/aspose.slides/iloadoptions/blob_management_options/) | Binary Large Object(BLOB) 처리 동작을 관리하는 데 사용할 수 있는 옵션을 나타냅니다.<br/>            임시 파일 사용이나 메모리 내 최대 BLOB 바이트 수와 같은 옵션을 포함합니다. 이러한 옵션은 특정 환경 또는 요구 사항에 맞게 최상의 성능/메모리 사용 비율을 설정하기 위해 의도되었습니다.<br/>            Binary Large Object(BLOB)는 단일 엔터티로 저장되는 바이너리 데이터이며, 예를 들어 오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다. |
| [`document_level_font_sources`](/slides/python-net/ko/aspose.slides/iloadoptions/document_level_font_sources/) | 프레젠테이션에서 사용할 외부 글꼴의 소스를 지정합니다.<br/>            이러한 글꼴은 프레젠테이션 수명 전체에 걸쳐 사용 가능하며 다른 프레젠테이션과 공유되지 않습니다. |
| [`interruption_token`](/slides/python-net/ko/aspose.slides/iloadoptions/interruption_token/) | 중단 요청을 감시하는 토큰입니다.<br/>            <br/>            이 토큰은 전체 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스 수명을 관리합니다. 프레젠테이션 로드 또는 저장과 같은 장기 실행 작업은 [`IInterruptionTokenSource`](/slides/python-net/ko/aspose.slides/iinterruptiontokensource)의 [`IInterruptionTokenSource.interrupt`](/slides/python-net/ko/aspose.slides/iinterruptiontokensource/interrupt) 메서드를 호출하여 중단됩니다. |
| [`resource_loading_callback`](/slides/python-net/ko/aspose.slides/iloadoptions/resource_loading_callback/) | 외부 리소스 로드를 관리하는 콜백 인터페이스를 반환하거나 설정합니다.<br/>            Read/write [`IResourceLoadingCallback`](/slides/python-net/ko/aspose.slides/iresourceloadingcallback). |
| [`spreadsheet_options`](/slides/python-net/ko/aspose.slides/iloadoptions/spreadsheet_options/) | 추가 스프레드시트 동작을 지정하는 데 사용할 수 있는 옵션을 나타냅니다. |
| [`default_text_language`](/slides/python-net/ko/aspose.slides/iloadoptions/default_text_language/) | 프레젠테이션 텍스트의 기본 언어를 반환하거나 설정합니다.<br/>             Read/write **str**. |
| [`delete_embedded_binary_objects`](/slides/python-net/ko/aspose.slides/iloadoptions/delete_embedded_binary_objects/) | 프레젠테이션 로드 중에 Aspose.Slides가 모든 포함된 바이너리 개체를 삭제할지 여부를 결정합니다.<br/>            <br/>포함된 바이너리 개체의 유형:<br/><br/><br/>* VBA 프로젝트 [`IPresentation.vba_project`](/slides/python-net/ko/aspose.slides/ipresentation/vba_project)<br/>* OLE 객체 포함 데이터 [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/ko/aspose.slides/ioleembeddeddatainfo/embedded_file_data)<br/>* ActiveX 컨트롤 바이너리 데이터 [`IControl.active_x_control_binary`](/slides/python-net/ko/aspose.slides/icontrol/active_x_control_binary)<br/><br/><br/>            Read/write **bool**. |

### 참조
* module [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)