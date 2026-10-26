---
title: WriteState
second_title: Aspose.Slides для C++ справочная документация API
description: Указывает состояние XmlWriter.
type: docs
weight: 755
url: /ru/system.xml/writestate/
---
## WriteState перечисление

Указывает состояние [XmlWriter](../xmlwriter/).

```cpp
enum class WriteState
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Start | 0 | Указывает, что метод XmlWriter::Write ещё не был вызван. |
| Prolog | 1 | Указывает, что пролог записывается. |
| Element | 2 | Указывает, что записывается начальный тег элемента. |
| Attribute | 3 | Указывает, что записывается значение атрибута. |
| Content | 4 | Указывает, что записывается содержимое элемента. |
| Closed | 5 | Указывает, что метод [XmlWriter::Close](../xmlwriter/close/) был вызван. |
| Error | 6 | Было выброшено исключение, которое оставило [XmlWriter](../xmlwriter/) в недопустимом состоянии. Вы можете вызвать метод [XmlWriter::Close](../xmlwriter/close/), чтобы перевести [XmlWriter](../xmlwriter/) в состояние [WriteState::Closed](./). Любые другие вызовы метода [XmlWriter](../xmlwriter/) приводят к InvalidOperationException. |

## См. также

* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)