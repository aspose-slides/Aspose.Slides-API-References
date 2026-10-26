---
title: Details_FileNotFoundException
second_title: Aspose.Slides for C++ API 레퍼런스
description: "디스크에 존재하지 않는 파일에 접근하려는 시도가 실패했을 때 발생하는 예외입니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 FileNotFoundException 클래스를 사용하십시오. FileNotFoundException 클래스 인스턴스를 System::SmartPtr에 감싸지 마십시오."
type: docs
weight: 183
url: /ko/system.io/details_filenotfoundexception/
---
## Details_FileNotFoundException 클래스

디스크에 존재하지 않는 파일에 접근하려는 시도가 실패했을 때 발생하는 예외입니다. 이 클래스를 직접 인스턴스화하지 마십시오. 대신 FileNotFoundException 클래스를 사용하십시오. FileNotFoundException 클래스 인스턴스를 [System::SmartPtr](../../system/smartptr/)에 감싸지 마십시오.

```cpp
class Details_FileNotFoundException : public System::Details_ExceptionWithFilename<Details_IOException>
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| virtual [String](../../system/string/) [get_FileName](../../system/details_exceptionwithfilename/get_filename/)() const | 이 예외를 일으키는 파일의 이름을 가져옵니다. |
| [String](../../system/string/) [get_Message](../../system/details_exceptionwithfilename/get_message/)() const override |  |
| [String](../../system/string/) [ToString](../../system/details_exceptionwithfilename/tostring/)() const override |  |

## 참고

* 클래스 [Details_ExceptionWithFilename](../../system/details_exceptionwithfilename/)
* 네임스페이스 [System::IO](../)
* 라이브러리 [Aspose.Slides](../../)