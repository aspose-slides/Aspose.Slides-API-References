---
title: ResourceLoadingAction
second_title: Aspose.Slides for C++ API 참조
description: 외부 리소스 로드 모드를 지정합니다.
type: docs
weight: 6761
url: /ko/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction 열거형

외부 리소스 로드 모드를 지정합니다.

```cpp
enum class ResourceLoadingAction
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../)은(는) 외부 리소스를 평소대로 로드합니다. |
| Skip | 1 | [Aspose.Slides](../)은(는) 외부 리소스 로드를 건너뜁니다. 이미지의 경우 데이터 없이 링크만 저장됩니다. |
| UserProvided | 2 | [Aspose.Slides](../)은(는) [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/)에서 사용자가 제공한 바이트 배열을 이미지 데이터로 사용합니다. |

## 관련 항목

* 네임스페이스 [Aspose::Slides](../)
* 라이브러리 [Aspose.Slides](../../)