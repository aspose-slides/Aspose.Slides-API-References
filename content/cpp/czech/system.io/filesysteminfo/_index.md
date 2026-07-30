---
title: FileSystemInfo
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: "Základní třída pro FileInfo a DirectoryInfo. Objekt této třídy by měl být alokován pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 300
url: /cs/system.io/filesysteminfo/
---
## FileSystemInfo třída

Základní třída pro [FileInfo](../fileinfo/) a [DirectoryInfo](../directoryinfo/). Objekt této třídy by měl být alokován pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo porušením aserce. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class FileSystemInfo : public System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [Delete](./delete/)() | Odstraní entitu reprezentovanou aktuálním objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [Finalize](./finalize/)() | Nevykonává nic. |
| [FileAttributes](../fileattributes/) [get_Attributes](./get_attributes/)() | Vrací atributy entity reprezentované aktuálním objektem. |
| [DateTime](../../system/datetime/) [get_CreationTime](./get_creationtime/)() | Vrací čas vytvoření entity reprezentované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](./get_creationtimeutc/)() | Vrací čas vytvoření entity reprezentované aktuálním objektem jako UTC čas. |
| virtual **bool** [get_Exists](./get_exists/)() | Určuje, zda entita odkazovaná cestou reprezentovanou aktuálním objektem existuje. |
| [String](../../system/string/) [get_Extension](./get_extension/)() | Vrací příponu souboru reprezentovaného aktuálním objektem. |
| virtual [String](../../system/string/) [get_FullName](./get_fullname/)() | Vrací úplný název (včetně cesty) entity reprezentované aktuálním objektem. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](./get_lastaccesstime/)() | Vrací čas posledního přístupu k entitě reprezentované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](./get_lastaccesstimeutc/)() | Vrací čas posledního přístupu k entitě reprezentované aktuálním objektem jako UTC čas. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](./get_lastwritetime/)() | Vrací čas posledního zápisu entity reprezentované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](./get_lastwritetimeutc/)() | Vrací čas posledního zápisu entity reprezentované aktuálním objektem jako UTC čas. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Vrací název entity reprezentované aktuálním objektem. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Ověří, zda objekt představuje instanci typu popsaného pomocí targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Volá se přímo nebo se použije objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| void [Refresh](./refresh/)() | Obnovuje stav aktuálního objektu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| void [set_Attributes](./set_attributes/)([FileAttributes](../fileattributes/)) | Nastaví zadané atributy na entitě reprezentované aktuálním objektem. |
| void [set_CreationTime](./set_creationtime/)([DateTime](../../system/datetime/)) | Nastaví čas vytvoření entity reprezentované aktuálním objektem jako lokální čas. |
| void [set_CreationTimeUtc](./set_creationtimeutc/)([DateTime](../../system/datetime/)) | Nastaví čas vytvoření entity reprezentované aktuálním objektem jako UTC čas. |
| void [set_LastAccessTime](./set_lastaccesstime/)([DateTime](../../system/datetime/)) | Nastaví čas posledního přístupu k entitě reprezentované aktuálním objektem jako lokální čas. |
| void [set_LastAccessTimeUtc](./set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Nastaví čas posledního přístupu k entitě reprezentované aktuálním objektem jako UTC čas. |
| void [set_LastWriteTime](./set_lastwritetime/)([DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu entity reprezentované aktuálním objektem jako lokální čas. |
| void [set_LastWriteTimeUtc](./set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Nastaví čas posledního zápisu entity reprezentované aktuálním objektem jako UTC čas. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí výrazu C# lock(). Volá se přímo nebo se použije objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Obor názvů [System::IO](../)
* Knihovna [Aspose.Slides](../../)