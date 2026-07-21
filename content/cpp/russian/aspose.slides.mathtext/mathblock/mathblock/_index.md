---
title: MathBlock()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр класса MathBlock.
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() конструктор

Инициализирует новый экземпляр класса [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Примечания

Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) конструктор

Создаёт новый математический блок и помещает в него указанный элемент.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Математический элемент, который необходимо поместить в блок |
## Примечания

Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) конструктор

Создаёт новый математический блок и помещает в него указанные элементы.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Математические элементы, которые необходимо поместить в блок |
## Примечания

Пример: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [MathBlock](../)
* Класс [IMathElement](../../imathelement/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)