---
title: "System::Reflection"
second_title: Aspose.Slides C++ API 参考
description: 
type: docs
weight: 755
url: /zh/system.reflection/
---
## 类

| 类 | 描述 |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) 类描述程序集。由于 C# 与 C++ 的规则差异很大，支持有限。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，否则会导致运行时错误和/或断言失败。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [AssemblyName](./assemblyname/) | 定义程序集名称。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，否则会导致运行时错误和/或断言失败。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | 在运行程序集里注册类型的单例。 |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | 用于在运行程序集里注册类型的单例的基类型。 |
| [ConstructorInfo](./constructorinfo/) | 提供对构造函数元数据的访问。 |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException 被 Module.GetTypes 方法抛出，如果模块中的任何类加载失败。绝不要手动创建此类的实例。请改用 ReflectionTypeLoadException 类。绝不要将 ReflectionTypeLoadException 类实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | 通过反射调用的方法抛出 TargetInvocationException。绝不要手动创建此类的实例。请改用 TargetInvocationException 类。绝不要将 TargetInvocationException 类实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [FieldInfo](./fieldinfo/) | 发现字段的属性并提供对字段元数据的访问。 |
| [MemberInfo](./memberinfo/) | 提供成员的反射信息。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，否则会导致运行时错误和/或断言失败。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [MethodBase](./methodbase/) | 方法的基础信息。此类的对象只能使用 [System::MakeObject()](../system/makeobject/) 函数分配。绝不要在栈上或使用 operator new 创建此类型的实例，否则会导致运行时错误和/或断言失败。始终将此类封装为 [System::SmartPtr](../system/smartptr/) 指针，并使用该指针将其作为参数传递给函数。 |
| [MethodInfo](./methodinfo/) | 表示类方法的信息。 |
| [PropertyInfo](./propertyinfo/) | 表示属性信息。 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [BindingFlags](./bindingflags/) | 定义成员和类型的查找模式及绑定。 |
| [FieldAttributes](./fieldattributes/) | 反射的字段属性。 |
| [MemberTypes](./membertypes/) | 标记每种成员类型。 |
## 类型定义

| 类型定义 | 描述 |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | 如果模块中的任何类加载失败，Module.GetTypes 方法会抛出 ReflectionTypeLoadException。绝不要将 ReflectionTypeLoadException 类实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |
| [TargetInvocationException](./targetinvocationexception/) | 通过反射调用的方法抛出 TargetInvocationException。绝不要将 TargetInvocationException 类实例封装到 [System::SmartPtr](../system/smartptr/) 中。 |