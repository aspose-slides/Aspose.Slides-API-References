---
title: SlideShowTransition
second_title: Aspose.Slides для C++ справочник API
description: Представляет переход слайд-шоу.
type: docs
weight: 404
url: /ru/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition класс

Представляет переход слайд-шоу.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## Методы

| Метод | Описание |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Определяет, равны ли два экземпляра [SlideShowTransition](./). Чтение/запись **bool**. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой двойной точности в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | Этот атрибут указывает, будет ли показ слайдов переключаться на следующий слайд через определённое время. Чтение **bool**. |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | Указывает время в миллисекундах, после которого должен начаться переход. Это значение может использоваться вместе с атрибутом advClick. Если атрибут не указан, считается, что автоматическое переключение не будет происходить. Чтение **uint32_t**. |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | Указывает, будет ли клик мышью переключать слайд. Если атрибут не указан, считается, что значение true. Чтение **bool**. |
| **int32_t** [get_Duration](./get_duration/)() override | Получает длительность эффекта перехода слайда в миллисекундах. Чтение **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | Возвращает встроенные аудио данные. Чтение [IAudio](../../aspose.slides/iaudio/). |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | Указывает, является ли данный звук встроенным. Если атрибут установлен в true, приложение-генератор проверяет атрибут name, указанный для этого звука в его списке встроенных звуков, и может отобразить пользовательское имя или UI по необходимости. Чтение **bool**. |
| **bool** [get_SoundLoop](./get_soundloop/)() override | Этот атрибут указывает, будет ли звук зацикливаться до возникновения следующего звукового события в показе слайдов. Чтение **bool**. |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | Устанавливает или возвращает режим звука для перехода слайда. Чтение [TransitionSoundMode](../transitionsoundmode/). |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | Указывает человекочитаемое имя звука перехода. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) должен быть назначен для получения или установки имени звука. Чтение [System::String](../../system/string/). |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | Указывает скорость перехода, которая будет использоваться при переходе от текущего слайда к следующему. Чтение [TransitionSpeed](../transitionspeed/). |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | Тип перехода. Чтение [TransitionType](../transitiontype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) значение перехода показа. Только чтение [ITransitionValueBase](../itransitionvaluebase/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Служит хеш-функцией для конкретного типа, пригодной для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | Этот атрибут указывает, будет ли показ слайдов переключаться на следующий слайд через определённое время. Запись **bool**. |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | Указывает время в миллисекундах, после которого должен начаться переход. Это значение может использоваться вместе с атрибутом advClick. Если атрибут не указан, считается, что автоматическое переключение не будет происходить. Запись **uint32_t**. |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | Указывает, будет ли клик мышью переключать слайд. Запись **bool**. |
| void [set_Duration](./set_duration/)(**int32_t**) override | Устанавливает длительность эффекта перехода слайда в миллисекундах. Запись **int32_t**. |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | Устанавливает встроенные аудио данные. Запись [IAudio](../../aspose.slides/iaudio/). |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | Указывает, является ли звук встроенным. Если атрибут установлен в true, приложение-генератор проверяет атрибут name, указанный для этого звука в его списке встроенных звуков, и может отобразить пользовательское имя или UI по необходимости. Запись **bool**. |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | Этот атрибут указывает, будет ли звук зацикливаться до следующего звукового события в показе слайдов. Запись **bool**. |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | Устанавливает или возвращает режим звука для перехода слайда. Запись [TransitionSoundMode](../transitionsoundmode/). |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | Указывает человекочитаемое имя звука перехода. [ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) должен быть назначен для получения или установки имени звука. Запись [System::String](../../system/string/). |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | Указывает скорость перехода, используемую при переходе от текущего слайда к следующему. Запись [TransitionSpeed](../transitionspeed/). |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | Тип перехода. Запись [TransitionType](../transitiontype/). |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [DomObject](../../aspose.slides/domobject/)
* Класс [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* Пространство имён [Aspose::Slides::SlideShow](../)
* Библиотека [Aspose.Slides](../../)