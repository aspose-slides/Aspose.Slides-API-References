---
title: SetLicense()
second_title: Aspose.Slides для C++ справочник API
description: Лицензирует компонент.
type: docs
weight: 1
url: /ru/aspose.slides/ilicense/setlicense/
---
## ILicense::SetLicense(System::String) метод

Лицензирует компонент.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::String licenseName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | [System::String](../../../system/string/) | Может быть полным или коротким именем файла или именем встроенного ресурса. Используйте пустую строку, чтобы переключиться в режим оценки. |

## Примечания

Пытается найти лицензию в следующих местах:

1. Явный путь.
2. Папка сборки компонента.
3. Папка вызывающей сборки клиента.
4. Папка входной сборки.
5. Встроенный ресурс в вызывающей сборке клиента.

**Примечание:**В .NET Compact Framework лицензия ищется только в следующих местах:

1. Явный путь.
2. Встроенный ресурс в вызывающей сборке клиента.

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки и затем во встроенных ресурсах вызывающей сборки.

```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## ILicense::SetLicense(System::SharedPtr\<System::IO::Stream\>) метод

Лицензирует компонент.

```cpp
virtual void Aspose::Slides::ILicense::SetLicense(System::SharedPtr<System::IO::Stream> stream)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, содержащий лицензию. |

## Примечания

Используйте этот метод для загрузки лицензии из потока.

```cpp
auto license = MakeObject<License>();
license->SetLicense(myStream);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ILicense](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)