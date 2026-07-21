---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет математический элемент в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathelementcollection/add/
---
## IMathElementCollection::Add(System::SharedPtr\<IMathElement\>) метод


Добавляет математический элемент в конец коллекции.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Add(System::SharedPtr<IMathElement> item)=0
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | [IMathElement](../../imathelement/), который будет добавлен в конец коллекции. |
## Примечания



Пример: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
collection->Add(System::MakeObject<MathematicalText>(u"+"));
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)