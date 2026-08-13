---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API 참조
description: 메모리에서 모든 BLOB이 차지할 수 있는 최대 전체 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB이 메모리로 로드됩니다; 이 제한에 도달했을 때만 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오.
type: docs
weight: 92
url: /ko/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) 메서드

메모리에서 모든 BLOB이 차지할 수 있는 최대 전체 크기(바이트)를 정의합니다. 기본적으로 모든 BLOB이 메모리로 로드됩니다; 이 제한에 도달했을 때만 임시 파일과 같은 대체 메커니즘이 사용됩니다. BLOB을 메모리에 유지하면 성능이 최적화되지만 메모리 사용량이 크게 증가할 수 있습니다. 이 속성을 사용하여 환경이나 요구 사항에 맞게 동작을 조정하십시오.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```
## 비고

이 값은 [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/)가 false 로 설정된 경우 무시됩니다, 메모리는 그때 사용 가능한 유일한 저장 위치가 되며 메모리 내 BLOB 사용을 제한해도 효과가 없기 때문입니다.

기본값은 629,145,600 바이트(600 MB)입니다.

이 속성을 0으로 설정할 수 있지만, 작은 최소 메모리 양은 여전히 예약됩니다.
## 참조

* 클래스 [BlobManagementOptions](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)