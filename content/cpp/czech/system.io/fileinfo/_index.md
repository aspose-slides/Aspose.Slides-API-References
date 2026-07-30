---
title: FileInfo
second_title: Aspose.Slides pro C++ API Reference
description: "Reprezentuje cestu k souboru a soubor odkazovaný touto cestou a poskytuje metody pro jeho manipulaci. Objektů této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním assercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a používejte tento ukazatel k předávání jako argument funkcím."
type: docs
weight: 274
url: /cs/system.io/fileinfo/
---
## FileInfo třída

Represents a path to a file and a file referred to by this path and provides methods for manipulating it. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class FileInfo : public System::IO::FileSystemInfo
```

## Metody

| Metoda | Popis |
| --- | --- |
| [StreamWriterPtr](../../system/streamwriterptr/) [AppendText](./appendtext/)() | Otevře soubor reprezentovaný aktuálním objektem pro zápis textu pomocí kódování UTF-8, v režimu 'Append' bez sdílení. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&) | Kopíruje soubor reprezentovaný aktuálním objektem do zadaného umístění. Pokud cílový soubor již existuje, kopírování selže. |
| [FileInfoPtr](../../system/fileinfoptr/) [CopyTo](./copyto/)(const [String](../../system/string/)\&, **bool**) | Kopíruje soubor reprezentovaný aktuálním objektem do zadaného umístění. Parametr určuje, zda má být existující cílový soubor přepsán. |
| [FileStreamPtr](../../system/filestreamptr/) [Create](./create/)() | Vytvoří soubor na místě určeném cestou reprezentovanou aktuálním objektem a otevře jej pro čtení a zápis v režimu zkrácení a bez sdílení. |
| [StreamWriterPtr](../../system/streamwriterptr/) [CreateText](./createtext/)() | Vytvoří soubor na místě určeném cestou reprezentovanou aktuálním objektem a otevře jej pro zápis textu pomocí kódování UTF-8 bez sdílení. |
| void [Decrypt](./decrypt/)() | NEIMPLEMENTOVÁNO. |
| void [Delete](./delete/)() override | Odstraní soubor reprezentovaný aktuálním objektem. |
| void [Encrypt](./encrypt/)() | NEIMPLEMENTOVÁNO. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje srovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje srovnání s dvojitou přesností ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [FileInfo](./fileinfo/)(const [String](../../system/string/)\&) | Vytvoří novou instanci třídy [FileInfo](./), která reprezentuje zadaný soubor. |
| virtual void [Finalize](../filesysteminfo/finalize/)() | Nedělá nic. |
| [FileAttributes](../fileattributes/) [get_Attributes](../filesysteminfo/get_attributes/)() | Vrací atributy entity reprezentované aktuálním objektem. |
| [DateTime](../../system/datetime/) [get_CreationTime](../filesysteminfo/get_creationtime/)() | Vrací čas vytvoření entity reprezentované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_CreationTimeUtc](../filesysteminfo/get_creationtimeutc/)() | Vrací čas vytvoření entity reprezentované aktuálním objektem jako čas UTC. |
| [DirectoryInfoPtr](../../system/directoryinfoptr/) [get_Directory](./get_directory/)() | Vrací objekt [DirectoryInfo](../directoryinfo/), který reprezentuje adresář, ve kterém se nachází soubor reprezentovaný aktuálním objektem. |
| [String](../../system/string/) [get_DirectoryName](./get_directoryname/)() | Vrací úplný název adresáře, ve kterém se nachází soubor reprezentovaný aktuálním objektem. |
| **bool** [get_Exists](./get_exists/)() override | Vrací hodnotu, která udává, zda soubor existuje. |
| [String](../../system/string/) [get_Extension](../filesysteminfo/get_extension/)() | Vrací příponu souboru reprezentovaného aktuálním objektem. |
| virtual [String](../../system/string/) [get_FullName](../filesysteminfo/get_fullname/)() | Vrací úplný název (včetně cesty) entity reprezentované aktuálním objektem. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() | Vrací hodnotu, která udává, zda je nastaven atribut ReadOnly. |
| [DateTime](../../system/datetime/) [get_LastAccessTime](../filesysteminfo/get_lastaccesstime/)() | Vrací čas posledního přístupu k entitě reprezentované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_LastAccessTimeUtc](../filesysteminfo/get_lastaccesstimeutc/)() | Vrací čas posledního přístupu k entitě reprezentované aktuálním objektem jako čas UTC. |
| [DateTime](../../system/datetime/) [get_LastWriteTime](../filesysteminfo/get_lastwritetime/)() | Vrací čas posledního zápisu k entitě reprezentované aktuálním objektem jako lokální čas. |
| [DateTime](../../system/datetime/) [get_LastWriteTimeUtc](../filesysteminfo/get_lastwritetimeutc/)() | Vrací čas posledního zápisu k entitě reprezentované aktuálním objektem jako čas UTC. |
| **int64_t** [get_Length](./get_length/)() | Vrací velikost souboru v bajtech. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Vrací název souboru. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu referenčního čítače asociovanou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
| void [MoveTo](./moveto/)(const [String](../../system/string/)\&) | Přesune soubor reprezentovaný aktuálním objektem na zadané umístění. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/)) | Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu pro čtení a zápis a bez sdílení. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/)) | Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu, se specifikovaným typem přístupu a bez sdílení. |
| [FileStreamPtr](../../system/filestreamptr/) [Open](./open/)([FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/)) | Otevře soubor reprezentovaný aktuálním objektem ve specifikovaném režimu, se specifikovaným typem přístupu a možností sdílení. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenRead](./openread/)() | Otevře soubor reprezentovaný aktuálním objektem pouze pro čtení, v režimu 'Open' se sdíleným přístupem pro čtení. |
| [StreamReaderPtr](../../system/streamreaderptr/) [OpenText](./opentext/)() | Otevře existující soubor na místě určeném cestou reprezentovanou aktuálním objektem pro čtení textu pomocí kódování UTF-8 bez sdílení. |
| [FileStreamPtr](../../system/filestreamptr/) [OpenWrite](./openwrite/)() | Otevře soubor reprezentovaný aktuálním objektem pouze pro zápis, v režimu 'OpenOrCreate' bez sdílení. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| void [Refresh](../filesysteminfo/refresh/)() | Obnovuje stav aktuálního objektu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený referenční čítač o zadanou hodnotu. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Nahrazuje obsah určeného cílového souboru souborem reprezentovaným aktuálním objektem [FileInfo](./) a vytváří zálohu nahrazeného souboru. |
| [FileInfoPtr](../../system/fileinfoptr/) [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | Nahrazuje obsah určeného cílového souboru souborem reprezentovaným aktuálním objektem [FileInfo](./) a vytváří zálohu nahrazeného souboru. |
| void [set_Attributes](../filesysteminfo/set_attributes/)([FileAttributes](../fileattributes/)) | Nastavuje zadané atributy na entitu reprezentovanou aktuálním objektem. |
| void [set_CreationTime](../filesysteminfo/set_creationtime/)([DateTime](../../system/datetime/)) | Nastavuje čas vytvoření entity reprezentované aktuálním objektem jako lokální čas. |
| void [set_CreationTimeUtc](../filesysteminfo/set_creationtimeutc/)([DateTime](../../system/datetime/)) | Nastavuje čas vytvoření entity reprezentované aktuálním objektem jako čas UTC. |
| void [set_IsReadOnly](./set_isreadonly/)(**bool**) | Nastavuje nebo ruší atribut ReadOnly na souboru. |
| void [set_LastAccessTime](../filesysteminfo/set_lastaccesstime/)([DateTime](../../system/datetime/)) | Nastavuje čas posledního přístupu k entitě reprezentované aktuálním objektem jako lokální čas. |
| void [set_LastAccessTimeUtc](../filesysteminfo/set_lastaccesstimeutc/)([DateTime](../../system/datetime/)) | Nastavuje čas posledního přístupu k entitě reprezentované aktuálním objektem jako čas UTC. |
| void [set_LastWriteTime](../filesysteminfo/set_lastwritetime/)([DateTime](../../system/datetime/)) | Nastavuje čas posledního zápisu k entitě reprezentované aktuálním objektem jako lokální čas. |
| void [set_LastWriteTimeUtc](../filesysteminfo/set_lastwritetimeutc/)([DateTime](../../system/datetime/)) | Nastavuje čas posledního zápisu k entitě reprezentované aktuálním objektem jako čas UTC. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného referenčního čítače. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený referenční čítač. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený referenční čítač. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Vrací cestu reprezentovanou aktuálním objektem. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání pomocí C# příkazu lock(). Zavolejte přímo nebo použijte sentinel objekt [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý referenční čítač. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý referenční čítač. Nemělo by být voláno přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [FileSystemInfo](../filesysteminfo/)
* Jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)