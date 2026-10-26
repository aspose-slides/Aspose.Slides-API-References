---
title: DirectoryInfo
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Zastupuje cestu v souborovém systému, adresář, na který tato cesta odkazuje, a poskytuje instanční metody pro manipulaci s adresáři. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním aserce. Vždy obalte tuto třídu ukazatelem System::SmartPtr a použijte tento ukazatel k předání funkcím jako argument."
type: docs
weight: 248
url: /cs/system.io/directoryinfo/
---
## DirectoryInfo třída

Zastupuje cestu v souborovém systému, adresář, na který tato cesta odkazuje, a poskytuje instanční metody pro manipulaci s adresáři. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class DirectoryInfo : public System::IO::FileSystemInfo
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Create](./create/)() | Vytvoří adresář na cestě, kterou představuje aktuální objekt. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [CreateSubdirectory](./createsubdirectory/)(const [String](../../system/string/)\&) | Vytvoří podadresáře na zadané cestě. |
| void [Delete](./delete/)() override | Odstraní adresář, na který odkazuje cesta představovaná aktuálním objektem, pokud je adresář prázdný. |
| void [Delete](./delete/)(**bool**) | Odstraní adresář, na který odkazuje cesta představovaná aktuálním objektem. Parametr určuje, zda má být obsah adresáře rekurzivně odstraněn, pokud adresář není prázdný. |
| [DirectoryInfo](./directoryinfo/)(const [String](../../system/string/)\&) | Vytvoří instanci třídy [DirectoryInfo](./) na zadané cestě. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)() | Vrací iterovatelnou kolekci obsahující všechny adresáře umístěné v adresáři, který představuje aktuální objekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&) | Vyhledává adresáře, které splňují zadaná kritéria vyhledávání v adresáři představovaném aktuálním objektem. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\>\> [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledává adresáře, které splňují zadaná kritéria vyhledávání buď v adresáři představovaném aktuálním objektem, nebo v celém adresářovém stromu, jehož kořenem je adresář představovaný aktuálním objektem. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)() | Vrací iterovatelnou kolekci obsahující všechny soubory umístěné v adresáři, který představuje aktuální objekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&) | Vyhledává soubory, které splňují zadaná kritéria vyhledávání v adresáři představovaném aktuálním objektem. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileInfoPtr](../../system/fileinfoptr/)\>\> [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledává soubory, které splňují zadaná kritéria vyhledávání buď v adresáři představovaném aktuálním objektem, nebo v celém adresářovém stromu, jehož kořenem je adresář představovaný aktuálním objektem. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)() | Vrací iterovatelnou kolekci obsahující všechny soubory a adresáře umístěné v adresáři, který představuje aktuální objekt. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&) | Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání v adresáři představovaném aktuálním objektem. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\>\> [EnumerateFileSystemInfos](./enumeratefilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání buď v adresáři představovaném aktuálním objektem, nebo v celém adresářovém stromu, jehož kořenem je adresář představovaný aktuálním objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání s plovoucí čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání s plovoucí čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Nedělá nic. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Vrací atributy entity představované aktuálním objektem. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Vrací čas vytvoření entity představované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Vrací čas vytvoření entity představované aktuálním objektem jako čas UTC. |
| **bool** [get_Exists](./get_exists/)() override | Určuje, zda cesta představovaná aktuálním objektem odkazuje na existující adresář. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Vrací příponu souboru představovaného aktuálním objektem. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Vrací plné jméno (včetně cesty) entity představované aktuálním objektem. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Vrací čas posledního přístupu k entitě představované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Vrací čas posledního přístupu k entitě představované aktuálním objektem jako čas UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Vrací čas posledního zápisu entity představované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Vrací čas posledního zápisu entity představované aktuálním objektem jako čas UTC. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Vrací název entity, na kterou odkazuje cesta představovaná aktuálním objektem. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Parent](./get_parent/)() | Vrací sdílený ukazatel na objekt [DirectoryInfo](./), který představuje cestu odkazující na nadřazený adresář adresáře představovaného aktuálním objektem. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Root](./get_root/)() | Vrací sdílený ukazatel na objekt [DirectoryInfo](./), který představuje cestu odkazující na kořenový adresář adresáře představovaného aktuálním objektem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače referencí spojenou s objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)() | Vrací pole obsahující sdílené ukazatele na objekty [DirectoryInfo](./) představující všechny adresáře umístěné v adresáři představovaném aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&) | Vyhledává adresáře, které splňují zadaná kritéria vyhledávání v adresáři představovaném aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[DirectoryInfoPtr](../../system/directoryinfoptr/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledává adresáře, které splňují zadaná kritéria vyhledávání buď v adresáři představovaném aktuálním objektem, nebo v celém adresářovém stromu, jehož kořenem je adresář představovaný aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)() | Vrací pole obsahující sdílené ukazatele na objekty [FileInfo](../fileinfo/) představující všechny adresáře umístěné v adresáři představovaném aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&) | Vyhledává soubory, které splňují zadaná kritéria vyhledávání v adresáři představovaném aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[FileInfoPtr](../../system/fileinfoptr/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledává soubory, které splňují zadaná kritéria vyhledávání buď v adresáři představovaném aktuálním objektem, nebo v celém adresářovém stromu, jehož kořenem je adresář představovaný aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)() | Vrací pole obsahující sdílené ukazatele na objekty [FileSystemInfo](../filesysteminfo/) představující všechny soubory a adresáře umístěné v adresáři představovaném aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&) | Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání v adresáři představovaném aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[FileSystemInfoPtr](../../system/filesysteminfoptr/)\> [GetFileSystemInfos](./getfilesysteminfos/)(const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | Vyhledává soubory a adresáře, které splňují zadaná kritéria vyhledávání buď v adresáři představovaném aktuálním objektem, nebo v celém adresářovém stromu, jehož kořenem je adresář představovaný aktuálním objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte ochranný objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Přesune adresář představovaný aktuálním objektem a celý jeho obsah na určené místo. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává hodnotový typ objektu s nullptr podle reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| void [Refresh](../filesysteminfo/refresh/)() | Obnovuje stav aktuálního objektu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počet sdílených referencí o zadanou hodnotu. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Nastaví zadané atributy na entitě představované aktuálním objektem. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Nastaví čas vytvoření entity představované aktuálním objektem jako lokální čas. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Nastaví čas vytvoření entity představované aktuálním objektem jako čas UTC. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Nastaví čas posledního přístupu k entitě představované aktuálním objektem jako lokální čas. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Nastaví čas posledního přístupu k entitě představované aktuálním objektem jako čas UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu entity představované aktuálním objektem jako lokální čas. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu entity představované aktuálním objektem jako čas UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Vrací řetězec obsahující cestu představovanou aktuálním objektem. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny interní datové struktury. |

## Viz také

* Třída [FileSystemInfo](../filesysteminfo/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)