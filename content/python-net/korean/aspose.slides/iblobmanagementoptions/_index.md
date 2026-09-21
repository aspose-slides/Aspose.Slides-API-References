---
title: IBlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/iblobmanagementoptions/
---
## IBlobManagementOptions 클래스

BLOB(Binary Large Object)는 단일 엔터티로 저장되는 이진 데이터이며, 즉 BLOB는 
            오디오, 비디오 또는 프레젠테이션 자체가 될 수 있습니다. 메모리 사용량을 최적화하기 위해 다양한 기술이 사용됩니다 
            BLOB를 작업하는 동안—이미 프레젠테이션에 저장되어 있거나 프로그래밍을 통해 나중에 추가될 수 있습니다. 
            [`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions)을 사용하면 BLOB와 관련된 다양한 동작 측면을 변경할 수 있습니다 
            [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation) 인스턴스 수명 동안 처리를 위해.

The IBlobManagementOptions type exposes the following members:

## 속성

| 속성 | 설명 |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/) | 이 속성은 Presentation 클래스의 인스턴스가 소스 파일 <br/>            또는 스트림의 소유자가 될 수 있는지 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 <br/>            BLOB 작업 중 메모리 사용량과 성능을 향상시키는 데 도움이 되지만, 소스(스트림 또는 파일)는 <br/>            Presentation 인스턴스 수명 동안 변경할 수 없습니다. 예시는 다음과 같습니다: |
| [`is_temporary_files_allowed`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed/) | 이 속성은 BLOB 작업 중 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 <br/>            감소시키지만 파일을 생성할 권한이 필요합니다.<br/>            프레젠테이션 작업이 끝난 후 모든 파일은 삭제됩니다. |
| [`temp_files_root_path`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/temp_files_root_path/) | 임시 파일이 생성될 루트 경로입니다. 기본적으로 시스템 임시 디렉터리가 사용됩니다. <br/>            호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한을 가져야 합니다. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/) | 모든 BLOB가 메모리에서 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB는 <br/>            메모리에 로드되며, 이 한도에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB를 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 높아질 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오. |


### 참고
* 클래스 [`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions)
* 클래스 [`IPresentation`](/slides/python-net/ko/aspose.slides/ipresentation)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)