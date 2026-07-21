---
title: Insert()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет объект MathElement в коллекцию по указанному индексу.
type: docs
weight: 157
url: /ru/aspose.slides.mathtext/mathblock/insert/
---
## MathBlock::Insert(int32_t, System::SharedPtr\<IMathElement\>) метод


Вставляет объект MathElement в коллекцию по указанному индексу.

```cpp
void Aspose::Slides::MathText::MathBlock::Insert(int32_t index, System::SharedPtr<IMathElement> item) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому следует вставить MathElement. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Объект MathElement для вставки. |
## Примечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)