---
title: EnumerateDirectories()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает перечисляемую коллекцию, содержащую все каталоги, расположенные в каталоге, представляемом текущим объектом.
type: docs
weight: 105
url: /ru/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() метод


Возвращает перечисляемую коллекцию, содержащую все каталоги, расположенные в каталоге, представляемом текущим объектом.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) метод


Ищет каталоги, удовлетворяющие указанным критериям поиска, в каталоге, представляемом текущим объектом.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени каталогов, которые следует искать |

### Возвращаемое значение

Перечисляемая коллекция общих указателей на объекты [DirectoryInfo](../), представляющих найденные каталоги, имена которых соответствуют **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) метод


Ищет каталоги, удовлетворяющие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всем дереве каталогов, корневым элементом которого является каталог, представляемый текущим объектом.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | Шаблон имени каталогов, которые следует искать |
| searchOption | [SearchOption](../../searchoption/) | Указывает, должен ли поиск выполняться только в каталоге, представляемом текущим объектом, или во всем дереве каталогов, корневым элементом которого является каталог, представляемый текущим объектом |

### Возвращаемое значение

Перечисляемая коллекция общих указателей на объекты [DirectoryInfo](../), представляющих найденные каталоги, имена которых соответствуют **searchPattern**

## См. также

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)