---
title: "System::Reflection"
second_title: Aspose.Slides for C++ API Referansı
description: 
type: docs
weight: 755
url: /tr/system.reflection/
---
## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) sınıfı, derlemeyi tanımlar. Destek sınırlıdır çünkü kurallar C# ve C++ arasında oldukça farklıdır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığında veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [AssemblyName](./assemblyname/) | Derleme adını tanımlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığında veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Çalışan derlemede tür kaydetmek için tek örnek. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Çalışan derlemede tür kaydetmek için tek örneklerin temel türü. |
| [ConstructorInfo](./constructorinfo/) | Yapıcı meta verilerine erişim sağlar. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException, bir modüldeki sınıflardan herhangi biri yüklenemezse Module.GetTypes yöntemi tarafından fırlatılır. Bu sınıfın örneklerini manuel olarak asla oluşturmayın. Bunun yerine ReflectionTypeLoadException sınıfını kullanın. ReflectionTypeLoadException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine asla sarmalamayın. |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException, yansıma yoluyla çağrılan yöntemler tarafından fırlatılır. Bu sınıfın örneklerini manuel olarak asla oluşturmayın. Bunun yerine TargetInvocationException sınıfını kullanın. TargetInvocationException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine asla sarmalamayın. |
| [FieldInfo](./fieldinfo/) | Bir alanın özniteliklerini keşfeder ve alan meta verilerine erişim sağlar. |
| [MemberInfo](./memberinfo/) | Üyeler hakkında yansıma bilgisi sağlar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığında veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [MethodBase](./methodbase/) | Yöntem hakkında temel bilgi. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../system/makeobject/) fonksiyonu kullanılarak tahsis edilmelidir. Bu tür bir örnek hiçbir zaman yığında veya new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin. |
| [MethodInfo](./methodinfo/) | Sınıf yöntemi hakkında bilgiyi temsil eder. |
| [PropertyInfo](./propertyinfo/) | Özellik bilgilerini temsil eder. |
## Enumlar

| Enum | Açıklama |
| --- | --- |
| [BindingFlags](./bindingflags/) | Üyeleri ve tip arama modlarını ve bağlamaları tanımlar. |
| [FieldAttributes](./fieldattributes/) | Yansıtılmış alan öznitelikleri. |
| [MemberTypes](./membertypes/) | Her üye tipini işaretler. |
## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException, bir modüldeki sınıflardan herhangi biri yüklenemezse Module.GetTypes yöntemi tarafından fırlatılır. ReflectionTypeLoadException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine asla sarmalamayın. |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException, yansıma yoluyla çağrılan yöntemler tarafından fırlatılır. TargetInvocationException sınıfı örneklerini [System::SmartPtr](../system/smartptr/) içine asla sarmalamayın. |