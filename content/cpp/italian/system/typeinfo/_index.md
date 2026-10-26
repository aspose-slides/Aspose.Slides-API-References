---
title: TypeInfo
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta un tipo particolare e fornisce informazioni su di esso.
type: docs
weight: 1379
url: /it/system/typeinfo/
---
## TypeInfo classe

Rappresenta un tipo particolare e fornisce informazioni su di esso.

```cpp
class TypeInfo
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | Aggiunge l'attributo specificato all'elenco degli attributi del tipo. |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | Imposta il costruttore predefinito per il tipo T. |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | Imposta il costruttore predefinito tramite il functor che crea l'istanza della classe. |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | Aggiunge il membro specificato all'elenco dei membri del tipo. |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | Fornisce una struttura [TypeInfo](./) unica per il tipo **BoxedValue** da condividere tra più classi Boxed*. |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | NON IMPLEMENTATO. Restituisce un puntatore all'assembly in cui è dichiarato il tipo rappresentato dall'oggetto corrente. |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | NON IMPLEMENTATO. Restituisce il nome pienamente qualificato, includendo il nome dell'assembly, del tipo rappresentato dall'oggetto corrente. |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | Restituisce il descrittore del tipo base. |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | Ottiene un valore che indica se l'oggetto Type corrente ha parametri di tipo non ancora sostituiti da tipi specifici. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | Ottiene l'elenco dei membri con il nome specificato. |
| [String](../string/) [get_FullName](./get_fullname/)() const | Restituisce il nome pienamente qualificato (ma senza il nome dell'assembly) del tipo rappresentato dall'oggetto corrente. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | Ottiene un array degli argomenti di tipo generico per questo tipo. |
| **bool** [get_IsAbstract](./get_isabstract/)() const | Ottiene un valore che indica se il Type è astratto e deve essere sovrascritto. |
| **bool** [get_IsArray](./get_isarray/)() const | Ottiene un valore che indica se il tipo è un array. |
| **bool** [get_IsClass](./get_isclass/)() const | Ottiene un valore che indica se il Type è una classe o un delegato; cioè, non è un tipo valore o un'interfaccia. |
| **bool** [get_IsEnum](./get_isenum/)() const | Ottiene un valore che indica se il Type corrente rappresenta un'enumerazione. |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | Ottiene un valore che indica se il Type corrente rappresenta una definizione di tipo generico, da cui possono essere costruiti altri tipi generici. |
| **bool** [get_IsInterface](./get_isinterface/)() const | Ottiene un valore che indica se il Type è un'interfaccia; cioè, non è una classe o un tipo valore. |
| **bool** [get_IsSealed](./get_issealed/)() const | Ottiene un valore che indica se il Type è dichiarato sealed. |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | Ottiene un valore che indica se il Type è un tipo valore. |
| **bool** [get_IsVisible](./get_isvisible/)() const | Ottiene un valore che indica se il Type può essere accessibile da codice al di fuori dell'assembly. |
| [String](../string/) [get_Name](./get_name/)() const | Restituisce il nome del tipo rappresentato dall'oggetto corrente. |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Ottiene lo spazio dei nomi del Type. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | Cerca un costruttore pubblico di istanza i cui parametri corrispondono ai tipi nell'array specificato. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | cerca i costruttori definiti per il Type corrente, usando i BindingFlags specificati. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | Restituisce tutti i costruttori pubblici definiti per il Type corrente. |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | Cerca l'attributo personalizzato applicato con il tipo specificato e applicato al tipo rappresentato dall'oggetto corrente. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | Restituisce un array contenente gli oggetti che rappresentano tutti gli attributi personalizzati applicati al tipo. |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | Restituisce un array contenente gli oggetti che rappresentano attributi specifici applicati al tipo. |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | NON IMPLEMENTATO. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Cerca il campo specificato, usando le restrizioni di binding specificate. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Cerca i campi definiti per il Type corrente, usando le restrizioni di binding specificate. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | Ottiene un array degli argomenti di tipo generico per questo tipo. |
| int [GetHashCode](./gethashcode/)() const | Restituisce un codice hash associato a questa istanza. |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | Ottiene tutte le interfacce implementate o ereditate dal Type corrente. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | Ottiene l'elenco dei membri con il nome specificato. |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | Ottiene il metodo con il nome specificato. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | Restituisce tutte le proprietà pubbliche del Type corrente. |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | Cerca le proprietà del Type corrente, usando le restrizioni di binding specificate. |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | Ottiene il descrittore del tipo del parametro di template. |
| **uint32_t** [Hash](./hash/)() const | Restituisce un valore hash associato al tipo rappresentato dall'oggetto corrente. |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | Determina se un'istanza di un tipo specificato può essere assegnata a una variabile del tipo corrente. |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | NON IMPLEMENTATO. Indica se uno o più attributi del tipo specificato o dei suoi tipi derivati sono applicati a questo membro. |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Determina se l'oggetto specificato è un'istanza del tipo corrente. |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | Determina se il tipo rappresentato dall'oggetto corrente è una sottoclasse della classe specificata. |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | Determina se l'oggetto corrente e quello specificato [TypeInfo](./) non sono uguali. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Determina se l'oggetto [TypeInfo](./) corrente non è un oggetto nullo, ossia rappresenta qualche tipo. |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | Determina se l'oggetto corrente e quello specificato [TypeInfo](./) sono uguali. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Determina se l'oggetto [TypeInfo](./) corrente è un oggetto nullo, cioè non rappresenta alcun tipo. |
| void [reset](./reset/)() | Imposta [TypeInfo](./) a null. |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | Imposta un valore che indica se il Type è un tipo valore. |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | Imposta il descrittore del tipo base. |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | Imposta il descrittore del tipo del parametro di template. |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | Calcola l'hash per la stringa specificata. |
| [String](../string/) [ToString](./tostring/)() const | Restituisce una stringa contenente il nome del tipo rappresentato dall'oggetto corrente. |
| static const [TypeInfo](./)\& [Type](./type/)() | Restituisce un oggetto [TypeInfo](./) che rappresenta la classe [TypeInfo](./). |
|  [TypeInfo](./typeinfo/)() | Costruttore predefinito (nessun tipo impostato). |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | Costruttore di oggetto nullo (nessun tipo impostato). |
|  [TypeInfo](./typeinfo/)(const char_t *) | Costruttore. |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | Costruttore. |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | Costruttore. |

## Campi

| Campo | Descrizione |
| --- | --- |
| static [EmptyType](./emptytype/) | Costante che rappresenta una lista vuota di [TypeInfo](./). |
| static [EmptyTypes](./emptytypes/) | Costante che rappresenta una lista vuota di [TypeInfo](./). |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | Puntatore a funzione per costruire il tipo. |

## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)