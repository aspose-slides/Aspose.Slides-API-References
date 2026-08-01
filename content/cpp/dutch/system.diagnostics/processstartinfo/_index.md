---
title: ProcessStartInfo
second_title: Aspose.Slides voor C++ API Referentie
description: "Beschrijft proces startparameters. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze als argument aan functies door te geven."
type: docs
weight: 40
url: /nl/system.diagnostics/processstartinfo/
---
## ProcessStartInfo klasse

Beschrijft proces startparameters. Objecten van deze klasse mogen alleen worden toegewezen met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, aangezien dit zal leiden tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class ProcessStartInfo : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl floating point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl floating point-vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [String](../../system/string/) [get_Arguments](./get_arguments/)() const | Haalt procesargumenten op. |
| **bool** [get_CreateNoWindow](./get_createnowindow/)() const | Haalt NoWindow-eigenschap op. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [get_EnvironmentVariables](./get_environmentvariables/)() const | Haalt procesomgevingvariabelen op. |
| [String](../../system/string/) [get_FileName](./get_filename/)() const | Haalt procesbestandsnaam op. |
| **bool** [get_RedirectStandardError](./get_redirectstandarderror/)() const | Haalt RedirectStandardError-eigenschap op. |
| **bool** [get_RedirectStandardInput](./get_redirectstandardinput/)() const | Haalt RedirectStandardInput-eigenschap op. |
| **bool** [get_RedirectStandardOutput](./get_redirectstandardoutput/)() const | Haalt RedirectStandardOutput-eigenschap op. |
| **bool** [get_UseShellExecute](./get_useshellexecute/)() const | Haalt UseShellExecute-eigenschap op. |
| [ProcessWindowStyle](../processwindowstyle/) [get_WindowStyle](./get_windowstyle/)() const | Haalt vensterstijl op. |
| [String](../../system/string/) [get_WorkingDirectory](./get_workingdirectory/)() const | Haalt werkmap van het proces op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hash-generatie van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt daadwerkelijke type van object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of object een instantie van het type die door targetType wordt beschreven vertegenwoordigt. Analoge van C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieerconstructor. Kopieert feitelijk niets, alleen een nieuw object initialiseren en kopieerconstructie van subklassen mogelijk maken. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert feitelijk niets, alleen een nieuw object initialiseren en kopieerconstructie van subklassen mogelijk maken. |
|  [ProcessStartInfo](./processstartinfo/)() | Maakt leeg start-info object aan. |
|  [ProcessStartInfo](./processstartinfo/)(const [String](../../system/string/)\&) | Maakt start-info object aan. |
|  [ProcessStartInfo](./processstartinfo/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Maakt start-info object aan. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt gedeelde referentieteller met de opgegeven waarde. |
| void [set_Arguments](./set_arguments/)(const [String](../../system/string/)\&) | Stelt procesargumenten in. |
| void [set_CreateNoWindow](./set_createnowindow/)(**bool**) | Stelt NoWindow-eigenschap in. |
| void [set_FileName](./set_filename/)(const [String](../../system/string/)\&) | Stelt procesbestandsnaam in. |
| void [set_RedirectStandardError](./set_redirectstandarderror/)(**bool**) | Stelt RedirectStandardError-eigenschap in. |
| void [set_RedirectStandardInput](./set_redirectstandardinput/)(**bool**) | Stelt RedirectStandardInput-eigenschap in. |
| void [set_RedirectStandardOutput](./set_redirectstandardoutput/)(**bool**) | Stelt RedirectStandardOutput-eigenschap in. |
| void [set_UseShellExecute](./set_useshellexecute/)(**bool**) | Stelt UseShellExecute-eigenschap in. |
| void [set_WindowStyle](./set_windowstyle/)([ProcessWindowStyle](../processwindowstyle/)) | Stelt vensterstijl in. |
| void [set_WorkingDirectory](./set_workingdirectory/)(const [String](../../system/string/)\&) | Stelt werkmap van het proces in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'te sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt huidige waarde van gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/) methode. Maakt conversie van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Bibliotheek [Aspose.Slides](../../)