---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет Paragraph в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) метод


Добавляет [Paragraph](../../paragraph/) в конец коллекции.

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | [Paragraph](../../paragraph/), который будет добавлен в конец коллекции. |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) метод


Добавляет содержимое [ParagraphCollection](../../paragraphcollection/) в конец коллекции.

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | [ParagraphCollection](../../paragraphcollection/), который будет добавлен в конец коллекции. |

### Возвращаемое значение

Индекс, по которому [Paragraph](../../paragraph/) был добавлен, или -1, если нечего добавлять.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [IParagraphCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)