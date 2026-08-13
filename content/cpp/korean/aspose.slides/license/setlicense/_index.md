---
title: SetLicense()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 구성 요소에 라이선스를 적용합니다.
type: docs
weight: 14
url: /ko/aspose.slides/license/setlicense/
---
## License::SetLicense(System::String) 메서드

구성 요소에 라이선스를 적용합니다.

```cpp
void Aspose::Slides::License::SetLicense(System::String licenseName) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | 전체 파일 이름 또는 짧은 파일 이름, 혹은 삽입된 리소스의 이름이 될 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환합니다. |

## 비고

다음 위치에서 라이선스를 찾습니다:

1. 명시적 경로.
2. 구성 요소 어셈블리의 폴더.
3. 클라이언트 호출 어셈블리의 폴더.
4. 진입 어셈블리의 폴더.
5. 클라이언트 호출 어셈블리의 삽입된 리소스.

**Note:** .NET Compact Framework에서는 라이선스를 다음 위치에서만 찾습니다:

1. 명시적 경로.
2. 클라이언트 호출 어셈블리의 삽입된 리소스.

이 예제에서는 MyLicense.lic이라는 라이선스 파일을 구성 요소가 포함된 폴더, 호출 어셈블리가 포함된 폴더, 진입 어셈블리의 폴더에서 찾은 다음 호출 어셈블리의 삽입된 리소스에서 찾으려고 시도합니다.
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## License::SetLicense(System::SharedPtr\<System::IO::Stream\>) 메서드

구성 요소에 라이선스를 적용합니다.

```cpp
void Aspose::Slides::License::SetLicense(System::SharedPtr<System::IO::Stream> stream) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 라이선스를 포함하는 스트림입니다. |

## 비고

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [License](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)