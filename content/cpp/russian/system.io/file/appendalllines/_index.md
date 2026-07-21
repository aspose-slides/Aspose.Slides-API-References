---
title: AppendAllLines()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет строки из указанной коллекции строк в указанный файл, используя указанную кодировку, записывая каждую строку в новой строке. Если указанный файл не существует, он будет создан. Файл закрывается после записи всех строк.
type: docs
weight: 1
url: /ru/system.io/file/appendalllines/
---
## File::AppendAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) метод

Добавляет строки из указанной коллекции строк в указанный файл, используя указанную кодировку, записывая каждую строку в новой строке. Если указанный файл не существует, он будет создан. Файл закрывается после записи всех строк.

```cpp
static void System::IO::File::AppendAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | Путь к файлу, в который нужно добавить строки |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | Строки, которые нужно записать в файл |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Кодировка символов, которую следует использовать |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Класс [String](../../../system/string/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [File](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)