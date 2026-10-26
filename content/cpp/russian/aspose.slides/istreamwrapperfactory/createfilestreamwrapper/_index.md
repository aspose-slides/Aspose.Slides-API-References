---
title: CreateFileStreamWrapper()
second_title: Aspose.Slides для C++ справочник API
description: Создает FileStream с указанным путем и режимом создания.
type: docs
weight: 14
url: /ru/aspose.slides/istreamwrapperfactory/createfilestreamwrapper/
---
## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode) метод

Создает FileStream с указанным путем и режимом создания.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Имя файла [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Режим файла [System::IO::FileMode](../../../system.io/filemode/) |

### Возвращаемое значение

Обертка потока для COM-интерфейса [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateFileStreamWrapper(System::String, System::IO::FileMode, System::IO::FileAccess) метод

Создает FileStream с указанным путем, режимом создания и правом чтения/записи.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateFileStreamWrapper(System::String fileName, System::IO::FileMode fileMode, System::IO::FileAccess fileAccess)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | [System::String](../../../system/string/) | Имя файла [System::String](../../../system/string/) |
| fileMode | [System::IO::FileMode](../../../system.io/filemode/) | Режим файла [System::IO::FileMode](../../../system.io/filemode/) |
| fileAccess | [System::IO::FileAccess](../../../system.io/fileaccess/) | Доступ к файлу [System::IO::FileAccess](../../../system.io/fileaccess/) |

### Возвращаемое значение

Обертка потока для COM-интерфейса [IStreamWrapper](../../istreamwrapper/)

## См. также

* Перечисление [FileMode](../../../system.io/filemode/)
* Перечисление [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IStreamWrapper](../../istreamwrapper/)
* Класс [String](../../../system/string/)
* Класс [IStreamWrapperFactory](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)