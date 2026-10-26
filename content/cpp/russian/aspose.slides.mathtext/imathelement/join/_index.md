---
title: Join()
second_title: Aspose.Slides для C++ справочника API
description: Объединяет математический элемент и формирует математический блок
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) метод

Объединяет математический элемент и формирует математический блок

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Элемент, который будет объединён |

### Возвращаемое значение

Новый [IMathBlock](../../imathblock/), содержащий этот экземпляр и указанный аргумент

## Замечания



Пример: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) метод

Объединяет математический текст и формирует математический блок

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Математический текст для объединения |

### Возвращаемое значение

Новый [IMathBlock](../../imathblock/), содержащий этот экземпляр и указанный аргумент

## Замечания



Пример: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)