---
title: File
second_title: Aspose.Slides для C++ справочник API
description: Предоставляет методы для работы с файлами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо способом.
type: docs
weight: 261
url: /ru/system.io/file/
---
## File класс

Предоставляет методы для работы с файлами. Это статический тип без сервисов экземпляра. Вы никогда не должны создавать его экземпляры каким-либо образом.

```cpp
class File
```

## Методы

| Метод | Описание |
| --- | --- |
| static void [AppendAllLines](./appendalllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Добавляет строки из указанной коллекции строк в указанный файл, используя заданную кодировку, записывая каждую строку в новой строке. Если указанный файл не существует, он будет создан. Файл закрывается после записи всех строк. |
| static void [AppendAllText](./appendalltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Добавляет указанную строку в указанный файл, используя заданную кодировку. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)(const [String](../../system/string/)\&) | Создаёт объект [StreamWriter](../streamwriter/), который добавляет текст в указанный файл с кодировкой UTF-8. Если указанный файл не существует, он будет создан. |
| static void [Copy](./copy/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Копирует указанный файл в указанное место. Если файл назначения уже существует, параметр указывает, следует ли его перезаписать. |
| static [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)(const [String](../../system/string/)\&, **int32_t**, [FileOptions](../fileoptions/)) | Создаёт новый файл (или перезаписывает существующий) и открывает его для чтения и записи с указанным размером буфера и параметрами. |
| static [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)(const [String](../../system/string/)\&) | Создаёт новый или открывает существующий файл для записи текста в кодировке UTF-8. |
| static void [Decrypt](./decrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&) | Удаляет указанный файл или каталог. |
| static void [Encrypt](./encrypt/)(const [String](../../system/string/)\&) | NOT IMPLEMENTED. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | Определяет, указывает ли указанный путь на существующий файл. |
| static [FileAttributes](../fileattributes/) [GetAttributes](./getattributes/)(const [String](../../system/string/)\&) | Возвращает атрибуты указанного объекта. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | Возвращает время создания указанного объекта как локальное время. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | Возвращает время создания указанного объекта как время UTC. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | Возвращает время последнего доступа к указанному объекту как локальное время. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | Возвращает время последнего доступа к указанному объекту как время UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | Возвращает время последней записи в указанный объект как локальное время. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | Возвращает время последней записи в указанный объект как время UTC. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Перемещает указанный файл в новое место. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | Открывает указанный файл в указанном режиме для чтения и записи без совместного доступа. |
| static [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Открывает указанный файл в указанном режиме, с указанным типом доступа и параметром совместного доступа. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)(const [String](../../system/string/)\&) | Открывает указанный файл только для чтения в режиме «Open» с совместным доступом для чтения. |
| static [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Открывает указанный существующий файл для чтения текста с кодировкой UTF-8 без совместного доступа. |
| static [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)(const [String](../../system/string/)\&) | Открывает указанный файл только для записи в режиме «OpenOrCreate» без совместного доступа. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadAllBytes](./readallbytes/)(const [String](../../system/string/)\&) | Считывает содержимое указанного бинарного файла в массив байтов. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [ReadAllLines](./readalllines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Считывает содержимое указанного текстового файла построчно в массив строк, используя указанную кодировку символов. |
| static [String](../../system/string/) [ReadAllText](./readalltext/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Считывает содержимое указанного текстового файла в один объект [String](../../system/string/) с использованием указанной кодировки символов. |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\> [ReadLines](./readlines/)(const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Считывает содержимое указанного текстового файла построчно, используя указанную кодировку символов, и возвращает перечисляемую коллекцию строк, каждая из которых представляет одну строку содержимого файла. |
| static void [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Заменяет содержимое одного файла другим и создаёт резервную копию заменённого файла. |
| static void [SetAttributes](./setattributes/)(const [String](../../system/string/)\&, [FileAttributes](../fileattributes/)) | Устанавливает указанные атрибуты для указанного файла. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | NOT IMPLEMENTED. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время последней записи указанного объекта как локальное время. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | Устанавливает время последней записи указанного объекта как время UTC. |
| static void [WriteAllBytes](./writeallbytes/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Перезаписывает указанный бинарный файл и записывает в него указанные байты. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](../../system/string/)\>\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Создаёт новый текстовый файл или перезаписывает существующий и записывает все строки из указанной перечисляемой коллекции строк в него, каждую строку на новой строке, используя указанную кодировку. |
| static void [WriteAllLines](./writealllines/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Создаёт новый текстовый файл или перезаписывает существующий и записывает все строки из указанного массива строк в него, каждую строку на новой строке, используя указанную кодировку. |
| static void [WriteAllText](./writealltext/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Создаёт новый текстовый файл или перезаписывает существующий и записывает содержимое указанной строки в него, используя указанную кодировку. |

## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultBufferSize](./defaultbuffersize/) | Значение по умолчанию количества байтов, буферизуемых при чтении из файла и записи в файл. |

## См. также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)