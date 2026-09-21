---
title: set_license method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides/license/set_license/
weight: 40
---
## set_license(self, license_name) {#str}
구성 요소에 라이선스를 적용합니다.

```python
def set_license(self, license_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| license_name | **str** | 전체 파일 이름이거나 짧은 파일 이름, 또는 포함된 리소스 이름이 될 수 있습니다.<br/><br/>빈 문자열을 사용하면 평가 모드로 전환됩니다. |

### 비고

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 지정된 경로.

2. 구성 요소 어셈블리의 폴더.

3. 클라이언트 호출 어셈블리의 폴더.

4. 진입 어셈블리의 폴더.

5. 클라이언트 호출 어셈블리의 포함된 리소스.

**참고:** .NET Compact Framework에서는 다음 위치에서만 라이선스를 찾으려고 시도합니다:

1. 지정된 경로.

2. 클라이언트 호출 어셈블리의 포함된 리소스.

## set_license(self, stream) {#iorawiobase}
구성 요소에 라이선스를 적용합니다.

```python
def set_license(self, stream):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 라이선스를 포함하고 있는 스트림입니다. |

### 비고

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

### 참고
* 클래스 [`License`](/slides/python-net/ko/aspose.slides/license)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)