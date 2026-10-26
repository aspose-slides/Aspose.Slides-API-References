---
title: FileInfo
second_title: "Aspose.Slides voor C++ API-referentie"
description: "Stelt een pad naar een bestand en een bestand dat door dit pad wordt aangeduid voor en biedt methoden voor het manipuleren ervan. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze aan functies door te geven als argument."
type: docs
weight: 274
url: /nl/system.io/fileinfo/
---
## FileInfo klasse

Stelt een pad naar een bestand en een bestand dat door dit pad wordt aangeduid voor en biedt methoden voor het manipuleren ervan. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten oplevert. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze aan functies door te geven als argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Opent een bestand dat door het huidige object wordt vertegenwoordigd voor het schrijven van tekst met UTF-8-codering, in 'Append'-modus zonder delen. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Kopieert het bestand dat door het huidige object wordt vertegenwoordigd naar de opgegeven locatie. Als het doelbestand al bestaat, mislukt de kopie. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Kopieert het bestand dat door het huidige object wordt vertegenwoordigd naar de opgegeven locatie. Een parameter geeft aan of een bestaand doelbestand moet worden overschreven. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Maakt een bestand op de locatie die door het pad van het huidige object wordt aangegeven en opent het voor lezen en schrijven, in truncate-modus zonder delen. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Maakt een bestand op de locatie die door het pad van het huidige object wordt aangegeven en opent het voor het schrijven van tekst met UTF-8-codering zonder delen. |
| void [Decrypt](./decrypt/)() | NIET GEÏMPLENTEERD. |
| void [Delete](./delete/)() override | Verwijdert het bestand dat door het huidige object wordt vertegenwoordigd. |
| void [Encrypt](./encrypt/)() | NIET GEÏMPLENTEERD. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevende-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Construeert een nieuw exemplaar van de [FileInfo](./) klasse die het opgegeven bestand vertegenwoordigt. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Doet niets. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Retourneert de attributen van de entiteit die door het huidige object wordt vertegenwoordigd. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Retourneert de aanmaaktijd van de entiteit die door het huidige object wordt vertegenwoordigd als lokale tijd. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Retourneert de aanmaaktijd van de entiteit die door het huidige object wordt vertegenwoordigd als UTC-tijd. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Retourneert een [DirectoryInfo](../directoryinfo/) object dat een map vertegenwoordigt waarin het bestand dat door het huidige object wordt vertegenwoordigd zich bevindt. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Retourneert de volledige naam van de map waarin het bestand dat door het huidige object wordt vertegenwoordigd zich bevindt. |
| **bool** [get_Exists](./get_exists/)() override | Retourneert een waarde die aangeeft of het bestand bestaat. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Retourneert de extensie van het bestand dat door het huidige object wordt vertegenwoordigd. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Retourneert de volledige naam (inclusief pad) van de entiteit die door het huidige object wordt vertegenwoordigd. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Retourneert een waarde die aangeeft of het ReadOnly-attribuut is ingesteld. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Retourneert de laatste toegangstijd van de entiteit die door het huidige object wordt vertegenwoordigd als lokale tijd. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Retourneert de laatste toegangstijd van de entiteit die door het huidige object wordt vertegenwoordigd als UTC-tijd. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Retourneert de laatste schrijftijd van de entiteit die door het huidige object wordt vertegenwoordigd als lokale tijd. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Retourneert de laatste schrijftijd van de entiteit die door het huidige object wordt vertegenwoordigd als UTC-tijd. |
| **int64_t** [get_Length](./get_length/)() | Retourneert de grootte van het bestand in bytes. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retourneert de naam van het bestand. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge van C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type beschreven door targetType. Analoge van C#-operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementeert vergrendeling van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Verplaatst het bestand dat door het huidige object wordt vertegenwoordigd naar de opgegeven locatie. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets, maar initialiseert een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Opent het bestand dat door het huidige object wordt vertegenwoordigd in de opgegeven modus voor lezen en schrijven, zonder delen. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Opent het bestand dat door het huidige object wordt vertegenwoordigd in de opgegeven modus, met het opgegeven toegangstype en zonder delen. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Opent het bestand dat door het huidige object wordt vertegenwoordigd in de opgegeven modus, met het opgegeven toegangstype en deeloptie. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Opent een bestand dat door het huidige object wordt vertegenwoordigd alleen voor lezen, in 'Open'-modus met gedeelde toegang voor lezen. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Opent het bestaande bestand op de locatie die door het pad van het huidige object wordt aangegeven voor het lezen van tekst met UTF-8-codering, zonder delen. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Opent een bestand dat door het huidige object wordt vertegenwoordigd alleen voor schrijven, in 'OpenOrCreate'-modus zonder delen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets, maar Initialiseert een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| void [Refresh](../filesysteminfo/refresh/)() | Vernieuwt de toestand van het huidige object. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Vervangt de inhoud van een opgegeven doelbestand door het bestand dat door het huidige [FileInfo](./) object wordt vertegenwoordigd en maakt een backup van het vervangen bestand. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Vervangt de inhoud van een opgegeven doelbestand door het bestand dat door het huidige [FileInfo](./) object wordt vertegenwoordigd en maakt een backup van het vervangen bestand. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Stelt de opgegeven attributen in op de entiteit die door het huidige object wordt vertegenwoordigd. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Stelt de aanmaaktijd van de entiteit die door het huidige object wordt vertegenwoordigd in als lokale tijd. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Stelt de aanmaaktijd van de entiteit die door het huidige object wordt vertegenwoordigd in als UTC-tijd. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Stelt het ReadOnly-attribuut van het bestand in of schakelt het uit. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Stelt de laatste toegangstijd van de entiteit die door het huidige object wordt vertegenwoordigd in als lokale tijd. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Stelt de laatste toegangstijd van de entiteit die door het huidige object wordt vertegenwoordigd in als UTC-tijd. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Stelt de laatste schrijftijd van de entiteit die door het huidige object wordt vertegenwoordigd in als lokale tijd. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Stelt de laatste schrijftijd van de entiteit die door het huidige object wordt vertegenwoordigd in als UTC-tijd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in op een zwakke pointer (in plaats van gedeeld). Maakt het mogelijk om pointers in containers te wijzigen naar zwakke modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retourneert een pad dat door het huidige object wordt vertegenwoordigd. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert ontgrendeling van de C# lock()-instructie. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [FileSystemInfo](../filesysteminfo/)
* Naamruimte [System::IO](../)
* Bibliotheek [Aspose.Slides](../../)