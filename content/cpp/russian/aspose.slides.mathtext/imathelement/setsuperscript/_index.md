---
title: SetSuperscript()
second_title: Aspose.Slides для C++ справка API
description: Создаёт надстрочный
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) метод


Создаёт надстрочный

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Надстрочный (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) метод


Создаёт надстрочный

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Надстрочный (верхний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)