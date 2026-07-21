---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт и записывает сущность суррогатного символа для пары суррогатных символов.
type: docs
weight: 391
url: /ru/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) метод

Генерирует и записывает сущность суррогатного символа для пары суррогатных символов.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| lowChar | char16_t | Нижний суррогат. Это должно быть значение между **0xDC00** и **0xDFFF**. |
| highChar | char16_t | Верхний суррогат. Это должно быть значение между **0xD800** и **0xDBFF**. |

## См. также

* Класс [XmlTextWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)