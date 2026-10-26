---
title: "System::Reflection"
second_title: Riferimento API di Aspose.Slides per C++
description: 
type: docs
weight: 755
url: /it/system.reflection/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Assembly](./assembly/) | [Reflection](./) classe che descrive l'assembly. Il supporto è limitato poiché le regole sono molto diverse tra C# e C++. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [AssemblyName](./assemblyname/) | Definisce il nome dell'assembly. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò proverà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [AssemblyTypeRegistration](./assemblytyperegistration/) | Singleton per registrare il tipo nell'assembly in esecuzione. |
| [AssemblyTypeRegistrationBase](./assemblytyperegistrationbase/) | Tipo base per singleton per registrare il tipo nell'assembly in esecuzione. |
| [ConstructorInfo](./constructorinfo/) | Fornisce l'accesso ai metadati del costruttore. |
| [Details_ReflectionTypeLoadException](./details_reflectiontypeloadexception/) | ReflectionTypeLoadException viene lanciata dal metodo Module.GetTypes se una delle classi in un modulo non può essere caricata. Non creare manualmente istanze di questa classe. Utilizzare la classe ReflectionTypeLoadException. Non avvolgere mai le istanze della classe ReflectionTypeLoadException in [System::SmartPtr](../system/smartptr/). |
| [Details_TargetInvocationException](./details_targetinvocationexception/) | TargetInvocationException viene lanciata dai metodi invocati tramite reflection. Non creare manualmente istanze di questa classe. Utilizzare la classe TargetInvocationException. Non avvolgere mai le istanze della classe TargetInvocationException in [System::SmartPtr](../system/smartptr/). |
| [FieldInfo](./fieldinfo/) | Scopre gli attributi di un campo e fornisce l'accesso ai metadati del campo. |
| [MemberInfo](./memberinfo/) | Fornisce informazioni di reflection sui membri. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò proverà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [MethodBase](./methodbase/) | Informazioni di base sul metodo. Gli oggetti di questa classe devono essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò proverà errori di runtime e/o fault di asserzione. Avvolgere sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usare questo puntatore per passarlo alle funzioni come argomento. |
| [MethodInfo](./methodinfo/) | Rappresenta le informazioni sul metodo di classe. |
| [PropertyInfo](./propertyinfo/) | Rappresenta le informazioni sulla proprietà. |
## Enumerazioni

| Enumerazione | Descrizione |
| --- | --- |
| [BindingFlags](./bindingflags/) | Definisce i membri e le modalità di ricerca e vincoli dei tipi. |
| [FieldAttributes](./fieldattributes/) | Attributi di campo riflessi. |
| [MemberTypes](./membertypes/) | Segna ogni tipo di membro. |
## Typedef

| Typedef | Descrizione |
| --- | --- |
| [ReflectionTypeLoadException](./reflectiontypeloadexception/) | ReflectionTypeLoadException viene lanciata dal metodo Module.GetTypes se una delle classi in un modulo non può essere caricata. Non avvolgere le istanze della classe ReflectionTypeLoadException in [System::SmartPtr](../system/smartptr/). |
| [TargetInvocationException](./targetinvocationexception/) | TargetInvocationException viene lanciata dai metodi invocati tramite reflection. Non avvolgere le istanze della classe TargetInvocationException in [System::SmartPtr](../system/smartptr/). |