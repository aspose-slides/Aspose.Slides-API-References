---
title: MathNaryOperator()
second_title: Aspose.Slides для C++ — справочник API
description: Создаёт новый экземпляр класса MathNaryOperator.
type: docs
weight: 183
url: /ru/aspose.slides.mathtext/mathnaryoperator/mathnaryoperator/
---
## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) конструктор


Создаёт новый экземпляр класса [MathNaryOperator](../).

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char16_t | Символ n-арного оператора |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Нижний предел |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Верхний предел |
## Примечания



Пример: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i=0"), System::MakeObject<MathematicalText>(u"\U0001d465"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) конструктор


Создаёт новый экземпляр класса [MathNaryOperator](../).

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> lowerLimit)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char16_t | Символ n-арного оператора |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Нижний предел |
## Примечания



Пример: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"), System::MakeObject<MathematicalText>(u"i"));
```

## MathNaryOperator::MathNaryOperator(char16_t, System::SharedPtr\<IMathElement\>) конструктор


Создаёт новый экземпляр класса [MathNaryOperator](../).

```cpp
Aspose::Slides::MathText::MathNaryOperator::MathNaryOperator(char16_t operatorSymbol, System::SharedPtr<IMathElement> baseArgument)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| operatorSymbol | char16_t | Символ n-арного оператора |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый аргумент |
## Примечания



Пример: 
```cpp
auto naryOperator = System::MakeObject<MathNaryOperator>(u'?', System::MakeObject<MathematicalText>(u"i"));
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)