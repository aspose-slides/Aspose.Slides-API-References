---
title: DirectoryInfo
second_title: Aspose.Slides voor C++ API-referentie
description: "Vertegenwoordigt een bestandssysteempad, een map die door dit pad wordt aangeduid, en biedt instantie-methoden voor het manipuleren van mappen. Objecten van deze klasse mogen alleen worden gealloceerd met de functie System::MakeObject() . Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assertiefouten veroorzaakt. Wikkel deze klasse altijd in een System::SmartPtr-pointer en gebruik deze pointer om deze aan functies als argument door te geven."
type: docs
weight: 248
url: /nl/system.io/directoryinfo/
---
## DirectoryInfo klasse

Representeert een bestandssysteempad, een map die door dit pad wordt aangeduid, en biedt instantie-methoden voor het manipuleren van mappen. Objecten van deze klasse mogen alleen worden gealloceerd met de functie [System::MakeObject()](../../system/makeobject/). Maak nooit een instantie van dit type op de stack of met operator new, omdat dit runtime-fouten en/of assert-fouten veroorzaakt. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om deze aan functies als argument door te geven.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Create](./create/)() | Maakt een map aan op het pad dat door het huidige object wordt gerepresenteerd. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Maakt submappen aan op het opgegeven pad. |
| void [Delete](./delete/)() override | Verwijdert de map die wordt aangeduid door het pad dat door het huidige object wordt gerepresenteerd, indien de map leeg is. |
| void [Delete](./delete/)(**bool**) | Verwijdert de map die wordt aangeduid door het pad dat door het huidige object wordt gerepresenteerd. Een parameter geeft aan of de inhoud van de map recursief moet worden verwijderd als de map niet leeg is. |
|  [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Construeert een instantie van de [DirectoryInfo](./)-klasse op het opgegeven pad. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Retourneert een enumerateerbare collectie met alle mappen die zich bevinden in de map die door het huidige object wordt gerepresenteerd. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt gerepresenteerd, hetzij in de volledige mapstructuur die in die map is geworteld. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Retourneert een enumerateerbare collectie met alle bestanden die zich bevinden in de map die door het huidige object wordt gerepresenteerd. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt gerepresenteerd, hetzij in de volledige mapstructuur die in die map is geworteld. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Retourneert een enumerateerbare collectie met alle bestanden en mappen die zich bevinden in de map die door het huidige object wordt gerepresenteerd. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt gerepresenteerd, hetzij in de volledige mapstructuur die in die map is geworteld. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Doet niets. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Retourneert de attributen van de entiteit die door het huidige object wordt gerepresenteerd. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Retourneert de creatietijd van de entiteit die door het huidige object wordt gerepresenteerd als lokale tijd. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Retourneert de creatietijd van de entiteit die door het huidige object wordt gerepresenteerd als UTC-tijd. |
| **bool** [get_Exists](./get_exists/)() override | Bepaalt of het pad dat door het huidige object wordt gerepresenteerd naar een bestaande map verwijst. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Retourneert de extensie van het bestand dat door het huidige object wordt gerepresenteerd. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Retourneert de volledige naam (incl. pad) van de entiteit die door het huidige object wordt gerepresenteerd. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Retourneert de laatste toegangstijd van de entiteit die door het huidige object wordt gerepresenteerd als lokale tijd. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Retourneert de laatste toegangstijd van de entiteit die door het huidige object wordt gerepresenteerd als UTC-tijd. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Retourneert de laatste schrijftijd van de entiteit die door het huidige object wordt gerepresenteerd als lokale tijd. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Retourneert de laatste schrijftijd van de entiteit die door het huidige object wordt gerepresenteerd als UTC-tijd. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Retourneert de naam van de entiteit waarnaar het pad dat door het huidige object wordt gerepresenteerd verwijst. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Retourneert een shared pointer naar een [DirectoryInfo](./)-object dat een pad representeert dat verwijst naar de bovenliggende map van de map die door het huidige object wordt gerepresenteerd. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Retourneert een shared pointer naar een [DirectoryInfo](./)-object dat een pad representeert dat verwijst naar de root-map van de map die door het huidige object wordt gerepresenteerd. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Retourneert een array met shared pointers naar [DirectoryInfo](./)-objecten die alle mappen representeren die zich bevinden in de map die door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt gerepresenteerd, hetzij in de volledige mapstructuur die in die map is geworteld. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Retourneert een array met shared pointers naar [FileInfo](../fileinfo/)-objecten die alle mappen representeren die zich bevinden in de map die door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt gerepresenteerd, hetzij in de volledige mapstructuur die in die map is geworteld. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Retourneert een array met shared pointers naar [FileSystemInfo](../filesysteminfo/)-objecten die alle bestanden en mappen representeren die zich bevinden in de map die door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria in de map die door het huidige object wordt gerepresenteerd. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Zoekt naar de bestanden en mappen die voldoen aan de opgegeven zoekcriteria, hetzij in de map die door het huidige object wordt gerepresenteerd, hetzij in de volledige mapstructuur die in die map is geworteld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analog van de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie vertegenwoordigt van het type dat door targetType wordt beschreven. Analog van de C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarbject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste typen mogelijk. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Verplaatst de map die door het huidige object wordt gerepresenteerd en al haar inhoud naar de opgegeven locatie. |
|  [Object](../../system/object/object/)() | Maakt een object aan. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert in feite niets, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert in feite niets, initialiseert enkel een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| void [Refresh](../filesysteminfo/refresh/)() | Ververs de status van het huidige object. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Stelt de opgegeven attributen in op de entiteit die door het huidige object wordt gerepresenteerd. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Stelt de creatietijd van de entiteit die door het huidige object wordt gerepresenteerd in als lokale tijd. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Stelt de creatietijd van de entiteit die door het huidige object wordt gerepresenteerd in als UTC-tijd. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Stelt de laatste toegangstijd van de entiteit die door het huidige object wordt gerepresenteerd in als lokale tijd. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Stelt de laatste toegangstijd van de entiteit die door het huidige object wordt gerepresenteerd in als UTC-tijd. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Stelt de laatste schrijftijd van de entiteit die door het huidige object wordt gerepresenteerd in als lokale tijd. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Stelt de laatste schrijftijd van de entiteit die door het huidige object wordt gerepresenteerd in als UTC-tijd. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n-de template-argument in als een weak-pointer (in plaats van shared). Maakt het wijzigen van pointers in containers naar weak-modus mogelijk. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Retourneert een string met het pad dat door het huidige object wordt gerepresenteerd. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert het C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het unlocken van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-waarbject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak-referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [FileSystemInfo](../filesysteminfo/)
* Naamruimte [System::IO](../)
* Library [Aspose.Slides](../../)