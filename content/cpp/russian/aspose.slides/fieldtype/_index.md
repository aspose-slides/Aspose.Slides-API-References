---
title: FieldType
second_title: Справочник API Aspose.Slides для C++
description: Представляет тип поля. Это значение определяет, какой текст будет установлен в части поля при её обновлении.
type: docs
weight: 872
url: /ru/aspose.slides/fieldtype/
---
## FieldType класс

Represents a type of field. This value determines which text will be set to the field portion when it will be updated.

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## Методы

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Checks if this field is equal to another. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
|  [FieldType](./fieldtype/)([System::String](../../system/string/)) | Initializes a new instance of [FieldType](./) class. |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | Текущие дата и время в формате даты и времени по умолчанию для приложения рендеринга. Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | Текущие дата и время в первом предопределённом формате (MM/DD/YYYY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | Текущие дата и время во втором предопределённом формате (hh:mm для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | Текущие дата и время в одиннадцатом предопределённом формате (hh:mm:ss для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | Текущие дата и время в двенадцатом предопределённом формате (hh:mm AM/PM для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | Текущие дата и время в тринадцатом предопределённом формате (hh:mm:ss AM/PM для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | Текущие дата и время во втором предопределённом формате (Day, Month DD, YYYY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | Текущие дата и время в третьем предопределённом формате (DD Month YYYY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | Текущие дата и время в четвёртом предопределённом формате (Month DD, YYYY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | Текущие дата и время в пятом предопределённом формате (DD-Mon-YY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | Текущие дата и время в шестом предопределённом формате (Month YY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | Текущие дата и время в седьмом предопределённом формате (Mon-YY для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | Текущие дата и время в восьмом предопределённом формате (MM/DD/YYYY hh:mm AM/PM для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | Текущие дата и время в девятом предопределённом формате (MM/DD/YYYY hh:mm:ss AM/PM для английского). Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | [Slide](../slide/)'s footer. Только для чтения [FieldType](./). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | [Slide](../slide/)'s header. Только для чтения [FieldType](./). |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | Возвращает внутреннее имя этого [FieldType](./) объекта. Чтение [System::String](../../system/string/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | Номер текущего слайда. Только для чтения [FieldType](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Возвращает хэш-код для этого объекта. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | Возвращает внутреннее имя этого [FieldType](./) объекта. Записать [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение общего счетчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [IFieldType](../ifieldtype/)
* Пространство имён [Aspose::Slides](../)
* Библиотека [Aspose.Slides](../../)