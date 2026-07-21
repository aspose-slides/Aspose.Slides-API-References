---
title: CspKeyContainerInfo
second_title: Aspose.Slides для C++ справочник API
description: Дополнительная информация о криптографической паре ключей.
type: docs
weight: 66
url: /ru/system.security.cryptography/cspkeycontainerinfo/
---
## CspKeyContainerInfo класс

Дополнительная информация о криптографической паре ключей.

```cpp
class CspKeyContainerInfo : public virtual System::Object
```

## Методы

| Method | Description |
| --- | --- |
|  [CspKeyContainerInfo](./cspkeycontainerinfo/)(const [SharedPtr](../../system/sharedptr/)\<[CspParameters](../cspparameters/)\>\&) | Конструктор. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa-значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_Accessible](./get_accessible/)() const | Возвращает флаг, указывающий, доступен ли ключ в контейнере. |
| **bool** [get_Exportable](./get_exportable/)() const | Возвращает флаг, указывающий, можно ли экспортировать ключ из контейнера. |
| **bool** [get_HardwareDevice](./get_hardwaredevice/)() const | Возвращает флаг, указывающий, является ли ключ аппаратным. |
| [String](../../system/string/) [get_KeyContainerName](./get_keycontainername/)() const | Возвращает имя контейнера ключа. |
| [SharedPtr](../../system/sharedptr/)\<[KeyNumber](../keynumber/)\> [get_KeyNumber](./get_keynumber/)() const | Возвращает объект KeyNumber. |
| **bool** [get_MachineKeyStore](./get_machinekeystore/)() const | Возвращает флаг, указывающий, загружен ли ключ из хранилища ключей машины. |
| **bool** [get_Protected](./get_protected/)() const | Возвращает флаг, указывающий, защищён ли ключ от копирования. |
| [String](../../system/string/) [get_ProviderName](./get_providername/)() const | Возвращает имя провайдера. |
| **int32_t** [get_ProviderType](./get_providertype/)() const | Возвращает тип провайдера. |
| **bool** [get_RandomlyGenerated](./get_randomlygenerated/)() const | Возвращает флаг, указывающий, был ли ключ сгенерирован случайным образом. |
| **bool** [get_Removable](./get_removable/)() const | Возвращает флаг, указывающий, можно ли удалить ключ из контейнера. |
| [String](../../system/string/) [get_UniqueKeyContainerName](./get_uniquekeycontainername/)() const | Возвращает уникальное имя контейнера. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует оператор блокировки C# `lock()`. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копирующее конструирование подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa-значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент в слабый указатель (а не в общий). Позволяет переключать указатели в контейнерах в режим слабых ссылок. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует счётчик общих ссылок. Не вызывается напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает счётчик общих ссылок. Не вызывается напрямую; используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку C# `lock()`. Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует счётчик слабых ссылок. Не вызывается напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует счётчик слабых ссылок. Не вызывается напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
## См. также

* Класс [Object](../../system/object/)
* Пространство имен [System::Security::Cryptography](../)
* Библиотека [Aspose.Slides](../../)