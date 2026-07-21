---
title: Remove()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет первое вхождение конкретного объекта из коллекции/>.
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) метод


Удаляет первое вхождение конкретного объекта из коллекции/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Объект, который необходимо удалить из коллекции. |

### Возвращаемое значение

true, если *item*  успешно удалён из коллекции; в противном случае — false. Этот метод также возвращает false, если *item*  не найден в исходной коллекции/>.

## Примечания



Пример: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [IMathBlockCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)