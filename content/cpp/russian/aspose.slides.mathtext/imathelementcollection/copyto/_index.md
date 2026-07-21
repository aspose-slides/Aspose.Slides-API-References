---
title: CopyTo()
second_title: Справочник API Aspose.Slides для C++
description: Копировать в указанный массив.
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imathelementcollection/copyto/
---
## IMathElementCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) method


Копировать в указанный массив.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | Массив, в который копировать. |
| arrayIndex | **int32_t** | Индекс, с которого начинается копирование. |
## Замечания



Пример: 
```cpp
System::SharedPtr<IMathElementCollection> collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(collection->get_Count());
collection->CopyTo(destinationArray, 0);
```

## См. также

* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)