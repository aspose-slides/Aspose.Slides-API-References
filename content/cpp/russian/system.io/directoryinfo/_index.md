---
title: DirectoryInfo
second_title: Справочник API Aspose.Slides для C++
description: "Представляет путь в файловой системе, каталог, на который указывает этот путь, и предоставляет методы экземпляра для управления каталогами. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 248
url: /ru/system.io/directoryinfo/
---
## DirectoryInfo класс

Представляет путь в файловой системе, каталог, на который указывает этот путь, и предоставляет методы экземпляра для управления каталогами. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Create](./create/)() | Создаёт каталог по пути, представляемому текущим объектом. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Создаёт вложенные каталоги по указанному пути. |
| void [Delete](./delete/)() override | Удаляет каталог, на который указывает путь, представляемый текущим объектом, если каталог пуст. |
| void [Delete](./delete/)(**bool**) | Удаляет каталог, на который указывает путь, представляемый текущим объектом. Параметр указывает, следует ли рекурсивно удалять содержимое каталога, если он не пуст. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Создаёт экземпляр класса [DirectoryInfo](./) по указанному пути. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Возвращает перечислимую коллекцию, содержащую все каталоги, находящиеся в каталоге, представляемом текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Ищет каталоги, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет каталоги, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Возвращает перечислимую коллекцию, содержащую все файлы, находящиеся в каталоге, представляемом текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Ищет файлы, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Возвращает перечислимую коллекцию, содержащую все файлы и каталоги, находящиеся в каталоге, представляемом текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Ищет файлы и каталоги, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы и каталоги, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Не делает ничего. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Возвращает атрибуты сущности, представляемой текущим объектом. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Возвращает время создания сущности, представляемой текущим объектом, как локальное время. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Возвращает время создания сущности, представляемой текущим объектом, как время UTC. |
| **bool** [get_Exists](./get_exists/)() override | Определяет, указывает ли путь, представляемый текущим объектом, на существующий каталог. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Возвращает расширение файла, представленного текущим объектом. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Возвращает полное имя (включая путь) сущности, представляемой текущим объектом. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Возвращает время последнего доступа к сущности, представляемой текущим объектом, как локальное время. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Возвращает время последнего доступа к сущности, представляемой текущим объектом, как время UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Возвращает время последней записи сущности, представляемой текущим объектом, как локальное время. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Возвращает время последней записи сущности, представляемой текущим объектом, как время UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Возвращает имя сущности, на которую указывает путь, представляемый текущим объектом. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Возвращает разделяемый указатель на объект [DirectoryInfo](./), представляющий путь к родительскому каталогу каталога, представленного текущим объектом. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Возвращает разделяемый указатель на объект [DirectoryInfo](./), представляющий путь к корневому каталогу каталога, представленного текущим объектом. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Возвращает массив, содержащий разделяемые указатели на объекты [DirectoryInfo](./), представляющие все каталоги, находящиеся в каталоге, представляемом текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Ищет каталоги, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет каталоги, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Возвращает массив, содержащий разделяемые указатели на объекты [FileInfo](../fileinfo/), представляющие все каталоги, находящиеся в каталоге, представляемом текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Ищет файлы, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Возвращает массив, содержащий разделяемые указатели на объекты [FileSystemInfo](../filesysteminfo/), представляющие все файлы и каталоги, находящиеся в каталоге, представляемом текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Ищет файлы и каталоги, соответствующие указанным критериям поиска, в каталоге, представляемом текущим объектом. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Ищет файлы и каталоги, соответствующие указанным критериям поиска, либо в каталоге, представляемом текущим объектом, либо во всём дереве каталогов, корнем которого является каталог, представляемый текущим объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного параметром targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Перемещает каталог, представляемый текущим объектом, и всё его содержимое в указанное место. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| void [Refresh](../filesysteminfo/refresh/)() | Обновляет состояние текущего объекта. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Устанавливает указанные атрибуты у сущности, представленной текущим объектом. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Устанавливает время создания сущности, представленной текущим объектом, как локальное время. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Устанавливает время создания сущности, представленной текущим объектом, как время UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Устанавливает время последнего доступа к сущности, представленной текущим объектом, как локальное время. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Устанавливает время последнего доступа к сущности, представленной текущим объектом, как время UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Устанавливает время последней записи сущности, представленной текущим объектом, как локальное время. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Устанавливает время последней записи сущности, представленной текущим объектом, как время UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в режим слабых ссылок. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Возвращает строку, содержащую путь, представляемый текущим объектом. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [FileSystemInfo](../filesysteminfo/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)