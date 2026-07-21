---
title: Join()
second_title: Aspose.Slides для C++: справочник API
description: Объединяет математический элемент и формирует математический блок
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) метод


Объединяет математический элемент и формирует математический блок

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, который будет объединён |

### Возвращаемое значение

Новый [IMathBlock](../../imathblock/), содержащий этот экземпляр и указанный аргумент
## Примечание



Пример: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) метод


Объединяет математический текст и формирует математический блок

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Математический текст, который будет объединён |

### Возвращаемое значение

Новый [IMathBlock](../../imathblock/), содержащий этот экземпляр и указанный аргумент
## Примечание



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)