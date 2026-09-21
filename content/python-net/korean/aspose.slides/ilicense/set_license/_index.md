---
title: set_license method
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
구성 요소에 라이선스를 적용합니다.


```python
def set_license(self, license_name):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| license_name | **str** | 전체 파일 이름이거나 짧은 파일 이름, 혹은 포함된 리소스의 이름이 될 수 있습니다.<br/><br/>            평가 모드로 전환하려면 빈 문자열을 사용합니다. |

### 비고

다음 위치에서 라이선스를 찾습니다:


1. 명시적인 경로.

2. 구성 요소 어셈블리의 폴더.

3. 클라이언트 호출 어셈블리의 폴더.

4. 엔트리 어셈블리의 폴더.

5. 클라이언트 호출 어셈블리 내에 포함된 리소스.

**참고:** .NET Compact Framework에서는 라이선스를 다음 위치에서만 찾습니다:


1. 명시적인 경로.

2. 클라이언트 호출 어셈블리 내에 포함된 리소스.

## set_license(self, stream) {#iorawiobase}
구성 요소에 라이선스를 적용합니다.


```python
def set_license(self, stream):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 라이선스를 포함하고 있는 스트림. |

### 비고

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.



### 또 보기
* 클래스 [`ILicense`](/slides/python-net/ko/aspose.slides/ilicense)
* 모듈 [`aspose.slides`](/slides/python-net/ko/aspose.slides)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)