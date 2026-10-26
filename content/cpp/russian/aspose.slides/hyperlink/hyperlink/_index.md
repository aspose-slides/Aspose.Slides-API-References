---
title: Hyperlink()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт экземпляр гиперссылки.
type: docs
weight: 339
url: /ru/aspose.slides/hyperlink/hyperlink/
---
## Hyperlink::Hyperlink(System::String) конструктор

Создаёт экземпляр гиперссылки.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::String url)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../) URL. |

## Hyperlink::Hyperlink(System::SharedPtr\<ISlide\>) конструктор

Создаёт экземпляр гиперссылки, указывающей на конкретный слайд. Примечание: созданная гиперссылка должна быть назначена объекту из той же презентации, иначе ссылка будет сохранена как NoAction.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<ISlide> slide)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | Целевой слайд. |

## Hyperlink::Hyperlink(System::SharedPtr\<Hyperlink\>, System::String, System::String, bool, bool, bool) конструктор

Создаёт экземпляр гиперссылки, используя другую гиперссылку в качестве источника, переопределяя вторичные свойства.

```cpp
Aspose::Slides::Hyperlink::Hyperlink(System::SharedPtr<Hyperlink> source, System::String targetFrame, System::String tooltip, bool history, bool stopSoundsOnClick, bool highlightClick)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [System::SharedPtr](../../../system/sharedptr/)\<[Hyperlink](../)\> | Исходная гиперссылка |
| targetFrame | [System::String](../../../system/string/) | Целевой фрейм |
| tooltip | [System::String](../../../system/string/) | Текст всплывающей подсказки |
| history | **bool** |  |
| stopSoundsOnClick | **bool** |  |
| highlightClick | **bool** |  |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Hyperlink](../)
* Класс [ISlide](../../islide/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)