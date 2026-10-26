---
title: "System::Reflection"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 755
url: /ru/system.reflection/
---
## Классы

| Класс | Описание |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) класс, описывающий сборку. Поддержка ограничена, так как правила сильно различаются между C# и C++. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или отказам утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [AssemblyName](./assemblyname/) | Определяет имя сборки. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или отказам утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Одиночка для регистрации типа в выполняемой сборке. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Базовый тип для одиночек, регистрирующих тип в выполняемой сборке. |
| [ConstructorInfo](./constructorinfo/) | Предоставляет доступ к метаданным конструктора. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException выбрасывается методом Module.GetTypes, если любой из классов в модуле не удаётся загрузить. Никогда не создавайте экземпляры этого класса вручную. Используйте класс ReflectionTypeLoadException вместо этого. Никогда не оборачивайте экземпляры класса ReflectionTypeLoadException в [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException выбрасывается методами, вызываемыми через отражение. Никогда не создавайте экземпляры этого класса вручную. Используйте класс TargetInvocationException вместо этого. Никогда не оборачивайте экземпляры класса TargetInvocationException в [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Обнаруживает атрибуты поля и предоставляет доступ к метаданным поля. |
| [MemberInfo](./memberinfo/) | Предоставляет информацию отражения о членах. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или отказам утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [MethodBase](./methodbase/) | Базовая информация о методе. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или отказам утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента. |
| [MethodInfo](./methodinfo/) | Представляет информацию о методе класса. |
| [PropertyInfo](./propertyinfo/) | Представляет информацию о свойстве. |
## Перечисления

| Перечисление | Описание |
| --- | --- |
| [BindingFlags](./bindingflags/) | Определяет членов и режимы поиска типов и привязки. |
| [FieldAttributes](./fieldattributes/) | Отражённые атрибуты поля. |
| [MemberTypes](./membertypes/) | Отмечает каждый тип члена. |
## Типы-определения

| Тип-определение | Описание |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException выбрасывается методом Module.GetTypes, если любой из классов в модуле не удаётся загрузить. Никогда не оборачивайте экземпляры класса ReflectionTypeLoadException в [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException выбрасывается методами, вызываемыми через отражение. Никогда не оборачивайте экземпляры класса TargetInvocationException в [System::SmartPtr](../system/smartptr/). |