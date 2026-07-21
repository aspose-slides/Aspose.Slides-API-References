---
title: MathAccent()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathaccent/mathaccent/
---
## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>) конструктор

Создаёт математический акцент, применяемый к указанному математическому элементу, со значением символа акцента по умолчанию

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется акцент |
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement);
```

## MathAccent::MathAccent(System::SharedPtr\<IMathElement\>, char16_t) конструктор

Создаёт математический акцент, применяемый к указанному математическому элементу

```cpp
Aspose::Slides::MathText::MathAccent::MathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется акцент |
| accentCharacter | char16_t | символ акцента |
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"x");
auto accent = System::MakeObject<MathAccent>(baseElement, u'~');
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathAccent](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)