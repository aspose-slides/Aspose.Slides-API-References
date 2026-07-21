---
title: MemoryStream
second_title: Справочник API Aspose.Slides для C++
description: "Представляет поток, который читает из памяти и записывает в неё. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 326
url: /ru/system.io/memorystream/
---
## MemoryStream класс

Представляет поток, который читает из памяти и записывает в неё. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class MemoryStream : public System::IO::Stream
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Инициирует асинхронную операцию чтения. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Инициирует асинхронную операцию записи. |
| void [Close](./close/)() override | Закрывает поток. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Копирует байты в указанный поток. |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | Копирует байты в указанный поток, используя указанный размер буфера. |
| void [Dispose](../stream/dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает поток. |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Ожидает завершения указанной асинхронной операции чтения. |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | Завершает асинхронную операцию записи. Ожидает завершения указанной асинхронной операции записи. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| void [Flush](./flush/)() override | Не делает ничего. |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно очищает все буферы этого потока, заставляет любые буферизованные данные записываться в нижележащее устройство и отслеживает запросы отмены. |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | Асинхронно очищает все буферы этого потока, заставляет любые буферизованные данные записываться в нижележащее устройство и отслеживает запросы отмены. |
| **bool** [get_CanRead](./get_canread/)() const override | Определяет, может ли поток читать. |
| **bool** [get_CanSeek](./get_canseek/)() const override | Определяет, поддерживает ли поток перемещение позиции. |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | Получает значение, определяющее, может ли текущий поток завершаться по тайм-ауту. |
| **bool** [get_CanWrite](./get_canwrite/)() const override | Определяет, может ли поток записывать. |
| int [get_Capacity](./get_capacity/)() | Возвращает текущую ёмкость базового буфера памяти. |
| **int64_t** [get_Length](./get_length/)() const override | Возвращает длину потока в байтах. |
| **int64_t** [get_Position](./get_position/)() const override | Возвращает текущую позицию потока. |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | Получает значение в миллисекундах, определяющее, как долго поток будет пытаться записывать до истечения тайм-аута. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBuffer](./getbuffer/)() | Возвращает указатель на базовый буфер. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [MemoryStream](./memorystream/)() | Создаёт новый экземпляр класса [MemoryStream](./) с начальной ёмкостью, равной 0. |
|  [MemoryStream](./memorystream/)(int) | Создаёт новый экземпляр класса [MemoryStream](./), представляющего поток, основанный на буфере памяти указанного размера. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **bool**) | Создаёт новый экземпляр класса [MemoryStream](./), представляющего поток памяти, подключённый к указанному буферу памяти. Параметр указывает, может ли поток записывать. |
|  [MemoryStream](./memorystream/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int, **bool**, **bool**) | Создаёт новый экземпляр класса [MemoryStream](./), представляющего поток памяти, подключённый к сегменту указанного буфера памяти, начинающемуся с указанного индекса и включающему заданное количество элементов. Параметры указывают, может ли поток записывать и можно ли вызвать метод GetBytes(). |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии в подклассах. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет создавать копии в подклассах. |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Считывает указанное количество байтов из потока и записывает их в указанный массив байтов. |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Считывает указанное количество байтов из потока и записывает их в указанный массив байтов. |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Считывает указанное количество байтов из потока и записывает их в указанный массив байтов. |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | Считывает указанное количество байтов из потока и записывает их в указанный диапазон байтов. |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно считывает последовательность байтов из текущего потока, перемещает позицию в потоке на количество считанных байтов и отслеживает запросы отмены. |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Асинхронно считывает последовательность байтов из текущего потока, перемещает позицию в потоке на количество считанных байтов и отслеживает запросы отмены. |
| int [ReadByte](./readbyte/)() override | Считывает один байт из потока и возвращает 32-битное целочисленное значение, соответствующее значению прочитанного байта. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнение по ссылке значимого типа с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | Устанавливает позицию потока, представленного текущим объектом. |
| void [set_Capacity](./set_capacity/)(int) | Устанавливает ёмкость базового буфера памяти. |
| void [set_Position](./set_position/)(**int64_t**) override | Устанавливает позицию потока. |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | Устанавливает значение, определяющее, может ли текущий поток завершаться по тайм-ауту. |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | Устанавливает значение в миллисекундах, определяющее, как долго поток будет пытаться читать до истечения тайм-аута. |
| void [SetLength](./setlength/)(**int64_t**) override | Устанавливает длину потока, представленного текущим объектом. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не разделяемый). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ToArray](./toarray/)() | Возвращает копию базового буфера памяти в виде массива байтов. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| **bool** [TryGetBuffer](./trygetbuffer/)([ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\&) | Возвращает массив беззнаковых байтов, из которого был создан этот поток. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Записывает указанный подпредел байтов из указанного массива байтов в поток. |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | Записывает указанный подпредел байтов из указанного массива байтов в поток. |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | Записывает указанный подпредел байтов из указанного массива байтов в поток. |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Записывает указанный подпредел байтов из указанного диапазона байтов в поток. |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены. |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Асинхронно записывает последовательность байтов в текущий поток, перемещает текущую позицию в этом потоке на количество записанных байтов и отслеживает запросы отмены. |
| void [WriteByte](./writebyte/)(**uint8_t**) override | Записывает указанное беззнаковое 8-битное целое значение в поток. |
| virtual void [WriteTo](./writeto/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>) | Записывает содержимое базового буфера в указанный поток. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static [Null](../stream/null/) | Поток без подлежащего хранилища. |

## Типы

| Тип | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним разделяемого указателя на самого себя. |

## Смотрите также

* Класс [Stream](../stream/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)