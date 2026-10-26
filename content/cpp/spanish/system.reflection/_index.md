---
title: "System::Reflection"
second_title: Referencia de API de Aspose.Slides para C++
description: 
type: docs
weight: 755
url: /es/system.reflection/
---
## Clases

| Clase | Descripción |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) clase que describe el ensamblado. El soporte es limitado ya que las reglas son bastante diferentes entre C# y C++. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [AssemblyName](./assemblyname/) | Define el nombre del ensamblado. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton para registrar el tipo en el ensamblado en ejecución. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Tipo base para singletons que registran el tipo en el ensamblado en ejecución. |
| [ConstructorInfo](./constructorinfo/) | Proporciona acceso a los metadatos del constructor. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException se lanza por el método Module.GetTypes si alguna de las clases en un módulo no se puede cargar. Nunca cree instancias de esta clase manualmente. Use la clase ReflectionTypeLoadException en su lugar. Nunca envuelva las instancias de la clase ReflectionTypeLoadException en [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException se lanza por los métodos invocados mediante reflexión. Nunca cree instancias de esta clase manualmente. Use la clase TargetInvocationException en su lugar. Nunca envuelva las instancias de la clase TargetInvocationException en [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Descubre los atributos de un campo y proporciona acceso a los metadatos del campo. |
| [MemberInfo](./memberinfo/) | Proporciona información de reflexión sobre los miembros. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [MethodBase](./methodbase/) | Información base sobre el método. Los objetos de esta clase solo deben asignarse usando la función [System::MakeObject()](../system/makeobject/). Nunca cree una instancia de este tipo en la pila o usando el operador new, ya que resultará en errores de tiempo de ejecución y/o fallos de aserción. Siempre envuelva esta clase en un puntero [System::SmartPtr](../system/smartptr/) y use ese puntero para pasarlo a funciones como argumento. |
| [MethodInfo](./methodinfo/) | Representa información sobre el método de la clase. |
| [PropertyInfo](./propertyinfo/) | Representa información de la propiedad. |
## Enumeraciones

| Enumeración | Descripción |
| --- | --- |
| [BindingFlags](./bindingflags/) | Define miembros y modos de búsqueda y vinculaciones de tipos. |
| [FieldAttributes](./fieldattributes/) | Atributos de campo reflejados. |
| [MemberTypes](./membertypes/) | Marca cada tipo de miembro. |
## Definiciones de tipos

| Definición de tipo | Descripción |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException se lanza por el método Module.GetTypes si alguna de las clases en un módulo no se puede cargar. Nunca envuelva las instancias de la clase ReflectionTypeLoadException en [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException se lanza por los métodos invocados mediante reflexión. Nunca envuelva las instancias de la clase TargetInvocationException en [System::SmartPtr](../system/smartptr/). |