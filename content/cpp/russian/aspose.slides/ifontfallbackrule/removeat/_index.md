---
title: RemoveAt()
second_title: Aspose.Slides для C++ — справочник API
description: Удаляет шрифт FallBack по указанному индексу в списке.
type: docs
weight: 92
url: /ru/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) метод

Удаляет шрифт FallBack по указанному индексу в списке.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс шрифта, который необходимо удалить. |
## Примечания



```cpp
// Создайте правило, содержащее список шрифтов.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Удаление Tahoma из списка
newRule->RemoveAt(2);
```


## См. также

* Класс [IFontFallBackRule](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)