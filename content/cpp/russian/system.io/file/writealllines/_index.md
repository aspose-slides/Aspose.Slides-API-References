---
title: WriteAllLines()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанной перечислимой коллекции строк в него, каждая строка записывается на новой строке, используя указанную кодировку.
type: docs
weight: 456
url: /ru/system.io/file/writealllines/
---
## File::WriteAllLines(const String\&, const SharedPtr\<Collections::Generic::IEnumerable\<String\>\>\&, const EncodingPtr\&) метод

Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанной перечислимой коллекции строк в него, каждая строка записывается на новой строке, используя указанную кодировку.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const SharedPtr<Collections::Generic::IEnumerable<String>> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The file to create or overwrite |
| contents | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../../../system/string/)\>\>\& | An enumerable collection of strings |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## File::WriteAllLines(const String\&, const ArrayPtr\<String\>\&, const EncodingPtr\&) метод

Создает новый текстовый файл или перезаписывает существующий и записывает все строки из указанного массива строк в него, каждая строка записывается на новой строке, используя указанную кодировку.

```cpp
static void System::IO::File::WriteAllLines(const String &path, const ArrayPtr<String> &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | The file to create or overwrite |
| contents | const [ArrayPtr](../../../system/arrayptr/)\<[String](../../../system/string/)\>\& | A string array |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | The character encoding to use |

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [EncodingPtr](../../../system/encodingptr/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [String](../../../system/string/)
* Класс [IEnumerable](../../../system.collections.generic/ienumerable/)
* Класс [File](../)
* Пространство имен [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)