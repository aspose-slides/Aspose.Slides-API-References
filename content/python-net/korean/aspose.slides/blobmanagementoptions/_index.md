---
title: BlobManagementOptions class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions 클래스

BLOB 처리 규칙 및 기타 BLOB 설정을 관리하는 데 사용할 수 있는 옵션을 나타냅니다.

BlobManagementOptions 유형은 다음 멤버를 노출합니다:

## 생성자

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/ko/aspose.slides/blobmanagementoptions/__init__/#) | 새 기본 blob 관리 옵션을 생성합니다. |

## 속성

| Property | Description |
| :- | :- |
| [`presentation_locking_behavior`](/slides/python-net/ko/aspose.slides/blobmanagementoptions/presentation_locking_behavior/) | 이 속성은 Presentation 클래스의 인스턴스가 수명 동안 소스 파일 <br/>            또는 스트림의 소유자가 될 수 있는지를 정의합니다. 인스턴스가 소유자인 경우 소스를 잠급니다. 이는 <br/>            BLOB 작업 시 메모리 사용량과 성능을 향상시키지만, 소스(스트림 또는 파일)는 <br/>            Presentation 인스턴스의 수명 동안 변경될 수 없습니다. |
| [`is_temporary_files_allowed`](/slides/python-net/ko/aspose.slides/blobmanagementoptions/is_temporary_files_allowed/) | 이 속성은 BLOB 작업 중 임시 파일을 생성할 수 있는지를 정의합니다. 이는 메모리 사용량을 크게 <br/>            감소시키지만 파일 생성 권한이 필요합니다.<br/>            모든 파일은 프레젠테이션 작업이 완료된 후 삭제됩니다. |
| [`temp_files_root_path`](/slides/python-net/ko/aspose.slides/blobmanagementoptions/temp_files_root_path/) | 임시 파일이 생성될 루트 경로입니다. 기본적으로 시스템 임시 디렉터리가 사용됩니다. <br/>            호스팅 프로세스는 해당 위치에 파일 및 폴더를 생성할 권한이 있어야 합니다. |
| [`max_blobs_bytes_in_memory`](/slides/python-net/ko/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/) | 메모리 내에서 모든 BLOB이 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB이 <br/>            메모리에 로드되며, 이 한도에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 높아질 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오. |

### 참고
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)