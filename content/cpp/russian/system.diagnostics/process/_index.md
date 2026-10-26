---
title: Process
second_title: Справочник API Aspose.Slides для C++
description: "Инкапсулирует информацию о процессе и его управление. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 27
url: /ru/system.diagnostics/process/
---
## Класс Process

Encapsulates process information and manipulation. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Process : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_EnableRaisingEvents](./get_enableraisingevents/)() const | Возвращает, следует ли поднимать событие Exited при завершении процесса. |
| int [get_ExitCode](./get_exitcode/)() const | Возвращает код завершения процесса. |
| **int64_t** [get_PrivateMemorySize64](./get_privatememorysize64/)() const | Возвращает размер частного набора памяти процесса. |
| [String](../../system/string/) [get_ProcessName](./get_processname/)() const | Возвращает имя процесса. |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardError](./get_standarderror/)() const | Предоставляет читатель для чтения вывода ошибок процесса. Not implemented. |
| [SharedPtr](../../system/sharedptr/)\<[System::IO::StreamReader](../../system.io/streamreader/)\> [get_StandardOutput](./get_standardoutput/)() const | Предоставляет читатель для чтения стандартного вывода процесса. Not implemented. |
| [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\> [get_StartInfo](./get_startinfo/)() const | Возвращает информацию о запуске процесса. |
| **int64_t** [get_WorkingSet64](./get_workingset64/)() const | Возвращает размер рабочего набора памяти процесса. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [GetCurrentProcess](./getcurrentprocess/)() | Возвращает информацию о текущем процессе. [Windows](../../system.windows/) only. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Enables hashing of custom objects. |
| [String](../../system/string/) [GetOutputText](./getoutputtext/)() const | Возвращает текст вывода процесса. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Создаёт объект. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значений со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_EnableRaisingEvents](./set_enableraisingevents/)(**bool**) | Устанавливает, следует ли поднимать событие Exited при завершении процесса. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не общий). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| **bool** [Start](./start/)() | Запускает процесс с предопределенными параметрами. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Запускает процесс с указанным путём и аргументами. |
| static [SharedPtr](../../system/sharedptr/)\<[Process](./)\> [Start](./start/)(const [SharedPtr](../../system/sharedptr/)\<[ProcessStartInfo](../processstartinfo/)\>\&) | Запускает процесс с указанным путём и аргументами. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| **bool** [WaitForExit](./waitforexit/)(int) | Ожидает завершения процесса. Not implemented. |
| void [WaitForExit](./waitforexit/)() | Ожидает завершения процесса, не возвращается, пока процесс не завершится. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Frees all internal data structures. |
| virtual  [~Process](./~process/)() | Деструктор. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Diagnostics](../)
* Библиотека [Aspose.Slides](../../)