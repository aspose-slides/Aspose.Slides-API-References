---
title: "System::Reflection"
second_title: "Referência da API Aspose.Slides para C++"
description: 
type: docs
weight: 755
url: /pt/system.reflection/
---
## Classes

| Classe | Descrição |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) classe que descreve o assembly. O suporte é limitado, pois as regras são bastante diferentes entre C# e C++. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. |
| [AssemblyName](./assemblyname/) | Define o nome do assembly. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton para registrar o tipo na assembly em execução. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Tipo base para singletons registrarem o tipo na assembly em execução. |
| [ConstructorInfo](./constructorinfo/) | Fornece acesso aos metadados do construtor. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException é lançada pelo método Module.GetTypes se alguma das classes em um módulo falhar ao carregar. Nunca crie instâncias desta classe manualmente. Use a classe ReflectionTypeLoadException em vez disso. Nunca envolva as instâncias da classe ReflectionTypeLoadException em [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException é lançada por métodos invocados via reflexão. Nunca crie instâncias desta classe manualmente. Use a classe TargetInvocationException em vez disso. Nunca envolva as instâncias da classe TargetInvocationException em [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Descobre os atributos de um campo e fornece acesso aos metadados do campo. |
| [MemberInfo](./memberinfo/) | Fornece informações de reflexão sobre os membros. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. |
| [MethodBase](./methodbase/) | Informação básica sobre o método. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../system/smartptr/) e use esse ponteiro para passá-la a funções como argumento. |
| [MethodInfo](./methodinfo/) | Representa informações sobre o método da classe. |
| [PropertyInfo](./propertyinfo/) | Representa informações de propriedade. |
## Enumeradores

| Enum | Descrição |
| --- | --- |
| [BindingFlags](./bindingflags/) | Define membros e modos de pesquisa e vinculação de tipos. |
| [FieldAttributes](./fieldattributes/) | Atributos de campo refletidos. |
| [MemberTypes](./membertypes/) | Marca cada tipo de membro. |
## Definições de Tipo

| Definição de Tipo | Descrição |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException é lançada pelo método Module.GetTypes se alguma das classes em um módulo falhar ao carregar. Nunca envolva as instâncias da classe ReflectionTypeLoadException em [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException é lançada por métodos invocados via reflexão. Nunca envolva as instâncias da classe TargetInvocationException em [System::SmartPtr](../system/smartptr/). |