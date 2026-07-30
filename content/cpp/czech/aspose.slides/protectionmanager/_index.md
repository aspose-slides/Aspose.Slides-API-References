---
title: ProtectionManager
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Správa ochrany prezentace heslem.
type: docs
weight: 4915
url: /cs/aspose.slides/protectionmanager/
---
## ProtectionManager třída

[Presentation](../presentation/) správa ochrany heslem.

```cpp
class ProtectionManager : public Aspose::Slides::IProtectionManager
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [CheckWriteProtection](./checkwriteprotection/)([System::String](../../system/string/)) override | Určuje, zda je prezentace chráněna heslem pro úpravy. |
| void [Encrypt](./encrypt/)([System::String](../../system/string/)) override | Šifruje [Presentation](../presentation/) pomocí zadaného hesla. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnávání floating-point ve stylu C#, kde jsou dvě NaN považována za rovná, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnávání floating-point ve stylu C#, kde jsou dvě NaN považována za rovná, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| **bool** [get_EncryptDocumentProperties](./get_encryptdocumentproperties/)() override | Tato vlastnost má smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou v souboru prezentace šifrovány vlastnosti dokumentu. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Číst **bool**. |
| [System::String](../../system/string/) [get_EncryptionPassword](./get_encryptionpassword/)() override | Získá heslo, které se používá pro šifrování prezentace. Pouze pro čtení [System::String](../../system/string/). |
| **bool** [get_IsEncrypted](./get_isencrypted/)() override | Získá hodnotu indikující, zda je tato instance šifrována. Pouze pro čtení **bool**. |
| **bool** [get_IsOnlyDocumentPropertiesLoaded](./get_isonlydocumentpropertiesloaded/)() override | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, ne jen vlastnosti dokumentu. Pokud prezentace není šifrována, je hodnota vlastnosti vždy false. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, je hodnota vlastnosti vždy false. Pokud je Presentation.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení **bool**. |
| **bool** [get_IsWriteProtected](./get_iswriteprotected/)() override | Získá hodnotu indikující, zda je tato prezentace chráněna proti zápisu. Pouze pro čtení **bool**. |
| **bool** [get_ReadOnlyRecommended](./get_readonlyrecommended/)() override | Získá doporučení pouze pro čtení. Číst **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu čítače odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie k metodě C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie k volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie k operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie k metodě C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nekopíruje nic, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nekopíruje nic, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenčně objekt typu hodnota s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač odkazů o zadanou hodnotu. |
| void [RemoveEncryption](./removeencryption/)() override | Odstraňuje šifrování. |
| void [RemoveWriteProtection](./removewriteprotection/)() override | Odstraňuje ochranu proti zápisu pro tuto prezentaci. |
| void [set_EncryptDocumentProperties](./set_encryptdocumentproperties/)(**bool**) override | Tato vlastnost má smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou v souboru prezentace šifrovány vlastnosti dokumentu. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Zapsat **bool**. |
| void [set_ReadOnlyRecommended](./set_readonlyrecommended/)(**bool**) override | Nastaví doporučení pouze pro čtení. Zapsat **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| void [SetWriteProtection](./setwriteprotection/)([System::String](../../system/string/)) override | Nastaví ochranu proti zápisu pro tuto prezentaci se zadaným heslem. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie k metodě C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolňuje všechny interní datové struktury. |

## Viz také

* Třída [IProtectionManager](../iprotectionmanager/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)