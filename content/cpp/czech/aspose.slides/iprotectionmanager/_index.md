---
title: IProtectionManager
second_title: Aspose.Slides pro C++ referenční příručka API
description: Správa ochrany prezentace heslem.
type: docs
weight: 3459
url: /cs/aspose.slides/iprotectionmanager/
---
## IProtectionManager třída

[Presentation](../presentation/) správa ochrany heslem.

```cpp
class IProtectionManager : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) | Určuje, zda je prezentace chráněna heslem pro úpravy. |
| virtual void [Encrypt](./encrypt/)([System::String](../../system/string/)) | Šifruje [Presentation](../presentation/) zadaným heslem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() | Tato vlastnost má smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu šifrovány v souboru prezentace. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Číst **bool**. |
| virtual [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() | Vrací šifrovací heslo. Pouze pro čtení [System::String](../../system/string/). |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() | Získá hodnotu udávající, zda je tato instance šifrována. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, ne pouze vlastnosti dokumentu. Pokud není prezentace šifrována, pak je hodnota vlastnosti vždy false. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, pak je hodnota vlastnosti vždy false. Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení **bool**. |
| virtual **bool** [get_IsWriteProtected](./get_iswriteprotected/)() | Získá hodnotu udávající, zda je tato prezentace chráněna proti zápisu. Pouze pro čtení **bool**. |
| virtual **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() | Získá doporučení pouze pro čtení. Číst **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt strážce. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Přiřazovací operátor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených odkazů o zadanou hodnotu. |
| virtual void [RemoveEncryption](./removeencryption/)() | Odstraňuje šifrování. |
| virtual void [RemoveWriteProtection](./removewriteprotection/)() | Odstraňuje ochranu proti zápisu pro tuto prezentaci. |
| virtual void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) | Tato vlastnost má smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu šifrovány v souboru prezentace. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Zapisovat **bool**. |
| virtual void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) | Nastavuje doporučení pouze pro čtení. Zapisovat **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| virtual void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) | Nastaví ochranu proti zápisu pro tuto prezentaci se zadaným heslem. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu čítače sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() příkazu. Zavolejte přímo nebo použijte [LockContext](../../system/lockcontext/) objekt strážce. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)