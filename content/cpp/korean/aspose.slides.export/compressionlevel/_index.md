---
title: CompressionLevel
second_title: Aspose.Slides for C++ API 참조
description: OpenXML 파일에 대한 ZIP 압축 레벨을 지정합니다. 높은 레벨일수록 압축 효율이 향상되지만 처리 속도가 느려집니다.
type: docs
weight: 846
url: /ko/aspose.slides.export/compressionlevel/
---
## CompressionLevel 열거형

OpenXML 파일에 대한 ZIP 압축 레벨을 지정합니다. 높은 레벨일수록 압축 효율이 개선되지만 처리 속도가 느려집니다.

```cpp
enum class CompressionLevel
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 압축이 적용되지 않습니다. 파일은 그대로 저장됩니다. |
| Level1 | 1 | 가장 낮은 압축 비율로 가장 빠른 압축을 제공합니다. |
| Level2 | 2 | [CompressionLevel::Level1](./)보다 약간 더 나은 압축 비율을 가진 더 빠른 압축을 제공합니다. |
| Level3 | 3 | [CompressionLevel::Level2](./)보다 더 나은 압축을 제공하지만 성능에 중간 정도 영향을 미칩니다. |
| Level4 | 4 | [CompressionLevel::Level3](./)보다 더 나은 압축을 제공합니다. |
| Level5 | 5 | [CompressionLevel::Level4](./)보다 향상된 압축을 제공하지만 추가 처리 시간이 필요합니다. |
| Level6 | 6 | 표준 압축으로 압축 속도와 파일 크기 사이의 균형을 잘 맞춥니다. 기본 압축 레벨입니다. |
| Level7 | 7 | [CompressionLevel::Level6](./)보다 더 높은 압축을 제공하지만 처리 속도가 느립니다. |
| Level8 | 8 | [CompressionLevel::Level7](./)보다 더 높은 압축을 제공합니다. |
| Level9 | 9 | 최대 압축을 제공합니다. 가장 작은 파일 크기를 생성하지만 처리 속도가 가장 느립니다. |

## 참고

* 네임스페이스 [Aspose::Slides::Export](../)
* 라이브러리 [Aspose.Slides](../../)