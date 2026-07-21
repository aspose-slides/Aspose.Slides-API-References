---
title: WriteSurrogateCharEntity()
second_title: Aspose.Slides для C++ справочник API
description: При переопределении в производном классе генерирует и записывает сущность суррогатного символа для пары суррогатных символов.
type: docs
weight: 261
url: /ru/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) метод


При переопределении в производном классе генерирует и записывает сущность суррогатного символа для пары суррогатных символов.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| lowChar | char16_t | Нижний суррогат. Это значение должно быть в диапазоне от 0xDC00 до 0xDFFF. |
| highChar | char16_t | Верхний суррогат. Это значение должно быть в диапазоне от 0xD800 до 0xDBFF. |

## Смотрите также

* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)