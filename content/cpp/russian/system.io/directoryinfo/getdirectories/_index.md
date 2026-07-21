---
title: GetDirectories()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает массив, содержащий разделяемые указатели на объекты DirectoryInfo, представляющие все каталоги, расположенные в каталоге, представляемом текущим объектом.
type: docs
weight: 144
url: /ru/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() метод

Возвращает массив, содержащий разделяемые указатели на объекты [DirectoryInfo](../), представляющие все каталоги, расположенные в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) метод

Ищет каталоги, которые удовлетворяют указанным условиям поиска, в каталоге, представляемом текущим объектом.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени каталогов для поиска |

### Возвращаемое значение

Массив разделяемых указателей на объекты [DirectoryInfo](../), представляющих найденные каталоги, имена которых соответствуют **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) метод

Ищет каталоги, которые удовлетворяют указанным условиям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени каталогов для поиска |
| searchOption | [SearchOption](../../searchoption/) | Указывает, следует ли выполнять поиск только в каталоге, представляемом текущим объектом, или во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом |

### Возвращаемое значение

Массив разделяемых указателей на объекты [DirectoryInfo](../), представляющих найденные каталоги, имена которых соответствуют **searchPattern**

## См. также

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Класс [DirectoryInfo](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)