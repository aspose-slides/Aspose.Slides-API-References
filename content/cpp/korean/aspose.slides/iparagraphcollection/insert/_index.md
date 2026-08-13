---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 컬렉션에 Paragraph를 삽입합니다.
type: docs
weight: 40
url: /ko/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) 메서드


지정된 인덱스에 컬렉션에 [Paragraph](../../paragraph/)를 삽입합니다.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | [Paragraph](../../paragraph/)가 삽입되어야 하는 0 기반 인덱스입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 삽입할 [Paragraph](../../paragraph/). |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) 메서드


지정된 인덱스에 컬렉션에 [ParagraphCollection](../../paragraphcollection/)의 내용을 삽입합니다.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 단락이 삽입될 0 기반 인덱스입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 삽입할 단락들. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IParagraph](../../iparagraph/)
* 클래스 [IParagraphCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)