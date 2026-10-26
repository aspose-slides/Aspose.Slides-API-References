---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: Paragraph를 컬렉션 끝에 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) 메서드


[Paragraph](../../paragraph/)를 컬렉션 끝에 추가합니다.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 컬렉션 끝에 추가될 [Paragraph](../../paragraph/). |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) 메서드


[ParagraphCollection](../../paragraphcollection/)의 내용을 컬렉션 끝에 추가합니다.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 컬렉션 끝에 추가될 [ParagraphCollection](../../paragraphcollection/). |

### 반환값

[Paragraph](../../paragraph/)가 추가된 인덱스이며, 추가할 것이 없으면 -1을 반환합니다.

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)