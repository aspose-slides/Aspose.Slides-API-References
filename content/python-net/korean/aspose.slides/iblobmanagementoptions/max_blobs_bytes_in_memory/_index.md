---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory 속성
모든 BLOB이 메모리에서 차지할 수 있는 최대 총 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB은 메모리로 로드됩니다; 이 한도에 도달하면 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오.

### 비고

메모리가 유일한 저장소가 되고 인메모리 BLOB 사용 제한이 효과가 없으므로 [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed)가 false로 설정되면 이 속성은 무시됩니다.

### 정의:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```

### 참고
* 클래스 [`IBlobManagementOptions`](/slides/python-net/ko/aspose.slides/iblobmanagementoptions)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)