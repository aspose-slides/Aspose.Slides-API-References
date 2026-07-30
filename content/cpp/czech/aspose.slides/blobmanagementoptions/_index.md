---
title: BlobManagementOptions
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje možnosti, které lze použít ke správě pravidel zacházení s BLOB a dalších nastavení BLOB.
type: docs
weight: 196
url: /cs/aspose.slides/blobmanagementoptions/
---
## BlobManagementOptions třída


Represents options which can be used to manage BLOB handling rules and other BLOB settings.

```cpp
class BlobManagementOptions : public Aspose::Slides::IBlobManagementOptions
```

## Metody

| Metoda | Popis |
| --- | --- |
|  [BlobManagementOptions](./blobmanagementoptions/)() | Vytvoří nové výchozí možnosti správy BLOB. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí čárky ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro vnitřní použití. |
| **bool** [get_IsTemporaryFilesAllowed](./get_istemporaryfilesallowed/)() override | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvořeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| **uint64_t** [get_MaxBlobsBytesInMemory](./get_maxblobsbytesinmemory/)() override | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (jako dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysokému využití paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům. |
| [Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/) [get_PresentationLockingBehavior](./get_presentationlockingbehavior/)() override | Tato vlastnost určuje, zda instance třídy [Presentation](../presentation/) může být vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, uzamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance [Presentation](../presentation/) měnit. |
| [System::String](../../system/string/) [get_TempFilesRootPath](./get_tempfilesrootpath/)() override | Kořenová cesta, kde budou vytvořeny dočasné soubory. Výchozí bude použita dočasná složka [System](../../system/). Hostitelský proces by měl mít oprávnění k vytváření souborů a složek v této cestě. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, jen inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| void [set_IsTemporaryFilesAllowed](./set_istemporaryfilesallowed/)(**bool**) override | Tato vlastnost určuje, zda mohou být během práce s BLOBy vytvořeny dočasné soubory, což výrazně snižuje spotřebu paměti, ale vyžaduje oprávnění k vytváření souborů. |
| void [set_MaxBlobsBytesInMemory](./set_maxblobsbytesinmemory/)(**uint64_t**) override | Definuje maximální celkovou velikost (v bajtech), kterou mohou všechny BLOBy zabírat v paměti. Ve výchozím nastavení jsou všechny BLOBy načteny do paměti; až po dosažení tohoto limitu jsou použity alternativní mechanismy (jako dočasné soubory). Udržování BLOBů v paměti maximalizuje výkon, ale může vést k vysokému využití paměti. Použijte tuto vlastnost k přizpůsobení chování vašemu prostředí nebo požadavkům. |
| void [set_PresentationLockingBehavior](./set_presentationlockingbehavior/)([Aspose::Slides::PresentationLockingBehavior](../presentationlockingbehavior/)) override | Tato vlastnost určuje, zda instance třídy [Presentation](../presentation/) může být vlastníkem zdroje – souboru nebo proudu během životnosti instance. Pokud je instance vlastníkem, uzamkne zdroj. To pomáhá zlepšit spotřebu paměti a výkon při práci s BLOBy, ale zdroj (proud nebo soubor) nelze během životnosti instance [Presentation](../presentation/) měnit. |
| void [set_TempFilesRootPath](./set_tempfilesrootpath/)([System::String](../../system/string/)) override | Kořenová cesta, kde budou vytvořeny dočasné soubory. Výchozí bude použita dočasná složka [System](../../system/). Hostitelský proces by měl mít oprávnění k vytváření souborů a složek v této cestě. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IBlobManagementOptions](../iblobmanagementoptions/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)