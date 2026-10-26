---
title: RemoveAt()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет шрифт FallBack по указанному индексу в списке.
type: docs
weight: 131
url: /ru/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) метод

Удаляет шрифт FallBack по указанному индексу в списке.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс шрифта, который нужно удалить. |
## Примечания

```cpp
// Создает правило, содержащее список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Удаляем Tahoma из списка.
newRule->RemoveAt(2);
```

## См. также

* Класс [FontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)