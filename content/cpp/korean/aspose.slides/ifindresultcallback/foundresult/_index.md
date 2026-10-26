---
title: FoundResult()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 검색된 텍스트에 대한 데이터를 수신하는 콜백 메서드입니다.
type: docs
weight: 1
url: /ko/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) 메서드


검색된 텍스트에 대한 데이터를 수신하는 콜백 메서드입니다.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | 텍스트가 발견된 [ITextFrame](../../itextframe/). |
| sourceText | [System::String](../../../system/string/) | 텍스트가 발견된 원본 텍스트. |
| foundText | [System::String](../../../system/string/) | 검색된 텍스트. |
| textPosition | **int32_t** | 검색된 텍스트의 위치. |

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITextFrame](../../itextframe/)
* 클래스 [String](../../../system/string/)
* 클래스 [IFindResultCallback](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)