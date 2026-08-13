---
title: InsertClone()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.
type: docs
weight: 66
url: /ko/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) 메서드

지정된 마스터 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다. 연결된 레이아웃 슬라이드도 복사됩니다.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) 복제할. |

### 반환값

삽입된 마스터 슬라이드.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMasterSlide](../../imasterslide/)
* 클래스 [IMasterSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)