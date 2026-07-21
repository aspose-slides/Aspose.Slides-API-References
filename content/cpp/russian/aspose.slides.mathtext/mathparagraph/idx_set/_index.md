---
title: idx_set()
second_title: Aspose.Slides для C++ справочник API
description: Получает элемент по указанному индексу. Только для чтения IMathBlock.
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/mathparagraph/idx_set/
---
## MathParagraph::idx_set(int32_t, System::SharedPtr\<IMathBlock\>) метод


Получает элемент по указанному индексу. Только для чтения [IMathBlock](../../imathblock/).

```cpp
void Aspose::Slides::MathText::MathParagraph::idx_set(int32_t index, System::SharedPtr<IMathBlock> value) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой базовый индекс элемента для получения |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Блок математического текста. |
## Примечания



Пример: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
auto block = mathParagraph->idx_get(1);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [MathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)