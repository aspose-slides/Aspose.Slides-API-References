---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션 끝에 Paragraph를 추가합니다.
type: docs
weight: 40
url: /ko/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) 메서드


컬렉션의 끝에 [Paragraph](../../paragraph/)을 추가합니다.

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```


### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 컬렉션 끝에 추가될 [Paragraph](../../paragraph/). |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) 메서드


컬렉션의 끝에 [ParagraphCollection](../)의 콘텐츠를 추가합니다.

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```


### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | 컬렉션 끝에 추가될 [ParagraphCollection](../). |

### 반환 값

추가된 [Paragraph](../../paragraph/)의 인덱스이며, 추가할 것이 없으면 -1을 반환합니다.

## 또 보기

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IParagraph](../../iparagraph/)
* 클래스 [ParagraphCollection](../)
* 클래스 [IParagraphCollection](../../iparagraphcollection/)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)