---
title: Join()
second_title: Справочник API Aspose.Slides для C++
description: Объединяет математический элемент с этим математическим блоком
type: docs
weight: 183
url: /ru/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) метод


Объединяет математический элемент с этим математическим блоком

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, который будет объединён |

### Возвращаемое значение

Текущий экземпляр [IMathBlock](../../imathblock/)
## Примечание



Пример: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) метод


Объединяет математический текст с этим математическим блоком

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
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
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)