---
title: Hyperlink()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 하이퍼링크의 인스턴스를 생성합니다.
type: docs
weight: 339
url: /ko/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) 생성자

하이퍼링크의 인스턴스를 생성합니다.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) 생성자

특정 슬라이드를 가리키는 하이퍼링크의 인스턴스를 생성합니다. 참고: 생성된 하이퍼링크는 동일한 프레젠테이션의 객체에 할당해야 하며, 그렇지 않으면 링크가 NoAction으로 저장됩니다.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | 대상 슬라이드. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) 생성자

다른 하이퍼링크를 소스로 사용하고 보조 속성을 재정의하여 하이퍼링크의 인스턴스를 생성합니다.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | 소스 하이퍼링크 |
| targetFrame | [System::String](../../../system/string/) | 대상 프레임 |
| tooltip | [System::String](../../../system/string/) | 툴팁 텍스트 |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Hyperlink](../)
* 클래스 [ISlide](../../islide/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)