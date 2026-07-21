---
title: MathArray
second_title: Aspose.Slides для C++ справочник API
description: Указывает вертикальный массив уравнений или любых математических объектов
type: docs
weight: 638
url: /ru/aspose.slides.mathtext/matharray/
---
## MathArray класс

Указывает вертикальный массив уравнений или любых математических объектов

```cpp
class MathArray : public Aspose::Slides::MathText::MathElementBase,
                  public Aspose::Slides::MathText::IMathArray
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](../mathelementbase/accent/)(char16_t) override | Устанавливает знак ударения (символ над этим элементом) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([System::String](../../system/string/)) override | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) override | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](../mathelementbase/asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) override | Принимает указанную функцию, используя этот экземпляр в качестве аргумента, и указанный дополнительный аргумент |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Создаёт дробь с этим числителем и указанным знаменателем |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/)) override | Создаёт дробь с этим числителем и указанным знаменателем |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathFractionTypes](../mathfractiontypes/)) override | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](../mathelementbase/divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) override | Создаёт дробь указанного типа с этим числителем и указанным знаменателем |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)() override | Заключает математический элемент в скобки |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](../mathelementbase/enclose/)(char16_t, char16_t) override | Заключает математический элемент в указанные символы, такие как скобки или другие символы в качестве рамки |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](../mathelementbase/function/)([System::String](../../system/string/)) override | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\> [get_Argument](./get_argument/)(**int32_t**) override | Возвращает элемент по указанному индексу массива. Только для чтения [Aspose::Slides::MathText::IMathElement](../imathelement/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathElementCollection](../imathelementcollection/)\> [get_Arguments](./get_arguments/)() override | Набор элементов массива |
| [MathVerticalAlignment](../mathverticalalignment/) [get_BaseJustification](./get_basejustification/)() override | Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему, верхнему краю или по центру объекта массива. Значение по умолчанию: Center |
| **bool** [get_MaximumDistribution](./get_maximumdistribution/)() override | Максимальное распределение. Когда истинно, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.). |
| **bool** [get_ObjectDistribution](./get_objectdistribution/)() override | Распределение объектов. Когда истинно, содержимое массива растягивается до максимальной ширины объекта массива. |
| **uint32_t** [get_RowSpacing](./get_rowspacing/)() override | Интервал между строками массива. Используется только когда RowSpacingRule установлен в 3: в этом случае единица измерения — пункты, или Multiple — в этом случае единица измерения — полулинии. Значение по умолчанию: 0 |
| [MathRowSpacingRule](../mathrowspacingrule/) [get_RowSpacingRule](./get_rowspacingrule/)() override | Тип вертикального интервала между элементами массива. Значение по умолчанию: SingleLineGap |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\> [GetChildren](./getchildren/)() override | Получить дочерние элементы |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)() override | Помещает этот элемент в группу, используя фигурную скобку снизу |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](../mathelementbase/group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) override | Помещает этот элемент в группу, используя символ группировки, такой как фигурная скобка снизу или иной |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [MathLimitLocations](../mathlimitlocations/)) override | Принимает интеграл |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Принимает интеграл |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/)) override | Принимает интеграл без пределов |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) override | Принимает интеграл |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](../mathelementbase/integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Принимает интеграл |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Объединяет математический элемент и формирует математический блок |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](../mathelementbase/join/)([System::String](../../system/string/)) override | Объединяет математический текст и формирует математический блок |
| void [Lock](../../system/object/lock/)() | Реализует оператор блокировки C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
|  [MathArray](./matharray/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | Создаёт математический массив и помещает в него указанный элемент |
|  [MathArray](./matharray/)([System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>\>\>) | Создаёт математический массив и помещает в него указанные элементы |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Создаёт N-арный оператор |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](../mathelementbase/nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) override | Создаёт N-арный оператор |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](../mathelementbase/overbar/)() override | Устанавливает черту наверху этого элемента |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Указывает математический корень заданной степени от указанного аргумента. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](../mathelementbase/radical/)([System::String](../../system/string/)) override | Указывает математический корень заданной степени от указанного аргумента. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_BaseJustification](./set_basejustification/)([MathVerticalAlignment](../mathverticalalignment/)) override | Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему, верхнему краю или по центру объекта массива. Значение по умолчанию: Center |
| void [set_MaximumDistribution](./set_maximumdistribution/)(**bool**) override | Максимальное распределение. Когда истинно, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.). |
| void [set_ObjectDistribution](./set_objectdistribution/)(**bool**) override | Распределение объектов. Когда истинно, содержимое массива растягивается до максимальной ширины объекта массива. |
| void [set_RowSpacing](./set_rowspacing/)(**uint32_t**) override | Интервал между строками массива. Используется только когда RowSpacingRule установлен в 3: в этом случае единица измерения — пункты, или Multiple — в этом случае единица измерения — полулинии. Значение по умолчанию: 0 |
| void [set_RowSpacingRule](./set_rowspacingrule/)([MathRowSpacingRule](../mathrowspacingrule/)) override | Тип вертикального интервала между элементами массива. Значение по умолчанию: SingleLineGap |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Принимает нижний предел |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](../mathelementbase/setlowerlimit/)([System::String](../../system/string/)) override | Принимает нижний предел |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Создаёт нижний индекс |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](../mathelementbase/setsubscript/)([System::String](../../system/string/)) override | Создаёт нижний индекс |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Создаёт нижний и верхний индексы слева |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](../mathelementbase/setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Создаёт нижний и верхний индексы слева |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Создаёт нижний и верхний индексы справа |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](../mathelementbase/setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Создаёт нижний и верхний индексы справа |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Создаёт верхний индекс |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](../mathelementbase/setsuperscript/)([System::String](../../system/string/)) override | Создаёт верхний индекс |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) override | Принимает верхний предел |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](../mathelementbase/setupperlimit/)([System::String](../../system/string/)) override | Принимает верхний предел |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)() override | Помещает этот элемент в границу-коробку |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](../mathelementbase/toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) override | Помещает этот элемент в границу-коробку |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](../mathelementbase/tobox/)() override | Помещает этот элемент в невизуальную коробку (логическую группировку), используемую для группировки компонентов уравнения или другого фрагмента математического текста. Такая коробка может, например, выступать в роли эмулятора оператора с точкой выравнивания или без неё, служить точкой разрыва строки или группировать так, чтобы внутри не допускались разрывы строк. |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](../mathelementbase/tomatharray/)() override | Размещает в вертикальном массиве |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](../mathelementbase/underbar/)() override | Устанавливает черту внизу этого элемента |
| void [Unlock](../../system/object/unlock/)() | Реализует оператор разблокировки C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не должно вызываться напрямую; используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Примечания

Пример: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## См. также

* Класс [MathElementBase](../mathelementbase/)
* Класс [IMathArray](../imatharray/)
* Пространство имён [Aspose::Slides::MathText](../)
* Библиотека [Aspose.Slides](../../)