---
title: License()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 1
url: /ko/aspose.slides/license/license/
---
## License::License() 생성자

이 클래스의 새 인스턴스를 초기화합니다.

```cpp
Aspose::Slides::License::License()
```

## 비고

이 예제에서는 컴포넌트를 포함하는 폴더, 호출 어셈블리를 포함하는 폴더, 진입 어셈블리의 폴더, 그리고 호출 어셈블리의 포함된 리소스에서 MyLicense.lic 라는 라이선스 파일을 찾으려고 시도합니다. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## 참고

* 클래스 [License](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)