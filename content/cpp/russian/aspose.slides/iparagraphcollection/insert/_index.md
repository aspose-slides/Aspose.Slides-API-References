---
title: Insert()
second_title: Aspose.Slides для C++ справочник API
description: Вставляет Paragraph в коллекцию по указанному индексу.
type: docs
weight: 40
url: /ru/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) метод

Вставляет [Paragraph](../../paragraph/) в коллекцию по указанному индексу.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Индекс, начинающийся с нуля, по которому будет вставлен [Paragraph](../../paragraph/). |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [Paragraph](../../paragraph/) для вставки. |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) метод

Вставляет содержимое [ParagraphCollection](../../paragraphcollection/) в коллекцию по указанному индексу.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Индекс, начинающийся с нуля, по которому будут вставлены абзацы. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | Абзацы для вставки. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IParagraph](../../iparagraph/)
* Класс [IParagraphCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)