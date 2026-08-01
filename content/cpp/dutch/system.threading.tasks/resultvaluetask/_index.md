---
title: ResultValueTask
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een hybride taakachtig type voor dat ofwel een directe resultaatwaarde of een ResultTask<T> kan omsluiten.
type: docs
weight: 53
url: /nl/system.threading.tasks/resultvaluetask/
---
## ResultValueTask klasse


Stelt een hybride taakachtig type voor dat ofwel een directe resultaatwaarde of een ResultTask<T> kan omsluiten.

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het resultaat dat door de taak wordt geproduceerd. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | Converteert dit [ResultValueTask](./) naar een gedeelde pointer naar ResultTask<T>. |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | Stelt een awaiter in voor deze taak. |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | Bepaalt of deze instantie gelijk is aan een andere [ResultValueTask](./) instantie. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bepaalt of deze instantie gelijk is aan een ander object. |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | Bepaalt of de huidige en opgegeven objecten gelijk zijn. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-achtige zwevende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-achtige zwevende-komma-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | Krijgt een waarde die aangeeft of de taak is beëindigd vanwege annulering. |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | Krijgt een waarde die aangeeft of de taak is voltooid. |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Krijgt een waarde die aangeeft of de taak succesvol is voltooid. |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | Krijgt een waarde die aangeeft of de taak is beëindigd door een onbehandelde uitzondering. |
| T [get_Result](./get_result/)() | Krijgt het resultaat van de voltooide taak. |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | Krijgt een awaiter voor deze taak om await-expressies te ondersteunen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Krijgt de referentieteller-datastructuur die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge aan C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Krijgt het werkelijke type van het object. Analoge aan C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat wordt beschreven door targetType. Analoge aan C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert lock()-statement vergrendeling uit C#. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakerobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | Ongelijkheidsoperator voor [ResultValueTask](./). |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | Gelijkheidsoperator voor [ResultValueTask](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
|  [ResultValueTask](./resultvaluetask/)() | Construeert een lege, niet-geïnitialiseerde [ResultValueTask](./). |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | Construeert een voltooide [ResultValueTask](./) met het opgegeven resultaat. |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | Construeert een [ResultValueTask](./) vanuit een gedeelde pointer naar een ResultTask<T>. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Krijgt de huidige waarde van de gedeelde referentieteller. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge aan C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert lock()-statement ontgrendeling uit C#. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakerobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
## Opmerkingen


[ResultValueTask](./) combineert de voordelen van [ValueTask](../valuetask/) (verlaagde allocaties voor synchroon resultaten) met het vermogen om bestaande ResultTask<T>-objecten te omhullen. Het biedt een await-bare interface en verschillende methoden voor het inspecteren van de taakstatus. 
## Zie ook

* Klasse [IEquatable](../../system/iequatable/)
* Naamruimte [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)