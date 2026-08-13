---
title: Insert()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에 컬렉션에 Paragraph를 삽입합니다.
type: docs
weight: 66
url: /ko/aspose.slides/paragraphcollection/insert/
---
## ParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) 메서드

컬렉션의 지정된 인덱스에 [Paragraph](../../paragraph/)를 삽입합니다.

```cpp
void Aspose::Slides::ParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | [Paragraph](../../paragraph/)가 삽입되어야 하는 0부터 시작하는 인덱스입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 삽입할 [Paragraph](../../paragraph/). |

## ParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) 메서드

컬렉션의 지정된 인덱스에 [ParagraphCollection](../)의 내용을 삽입합니다.

```cpp
void Aspose::Slides::ParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 문단이 삽입되어야 하는 0부터 시작하는 인덱스입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | 삽입할 문단들. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [ParagraphCollection](../)
* Class [IParagraphCollection](../../iparagraphcollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)