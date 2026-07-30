---
title: SymmetricAlgorithm
second_title: Aspose.Slides pro C++ API Reference
description: "Symetrický algoritmus používající stejný klíč pro šifrování i dešifrování, základní třída. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instance tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asertací. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a tento ukazatel použijte při předávání jako argument funkcím."
type: docs
weight: 651
url: /cs/system.security.cryptography/symmetricalgorithm/
---
## SymmetricAlgorithm třída

Symmetric algorithm using same key for encryption and decryption base class. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SymmetricAlgorithm : public virtual System::Object
```

## Metody

| Method | Description |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Vytvoří instanci algoritmu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | Vytvoří dešifrovací zařízení s parametry spojenými s objektem algoritmu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Vytvoří dešifrovací zařízení s explicitními parametry. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | Vytvoří šifrovací zařízení s parametry spojenými s objektem algoritmu. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Vytvoří šifrovací zařízení s explicitními parametry. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty podle sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [GenerateIV](./generateiv/)() | Vygeneruje náhodnou počáteční hodnotu pro algoritmus. Přepíše existující (pokud existuje). |
| virtual void [GenerateKey](./generatekey/)() | Vygeneruje náhodný klíč pro algoritmus. Přepíše existující (pokud existuje). |
| virtual int [get_BlockSize](./get_blocksize/)() | Získá velikost bloku kryptografické operace. |
| virtual int [get_FeedbackSize](./get_feedbacksize/)() | Získá velikost zpětné vazby kryptografické operace. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](./get_iv/)() | Získá počáteční hodnotu kryptografické operace. Vytvoří novou, pokud ještě neexistuje. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](./get_key/)() | Získá klíč kryptografické operace. Vytvoří nový, pokud ještě neexistuje. |
| virtual int [get_KeySize](./get_keysize/)() | Získá velikost klíče kryptografické operace. |
| virtual [CipherMode](../ciphermode/) [get_Mode](./get_mode/)() | Získá režim kryptografické operace. |
| virtual [PaddingMode](../paddingmode/) [get_Padding](./get_padding/)() | Získá výplň kryptografické operace. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zámek C# lock(). Zavolejte přímo nebo použijte objekt hlídače [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Skutečně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených odkazů o zadanou hodnotu. |
| virtual void [set_BlockSize](./set_blocksize/)(int) | Nastaví velikost bloku kryptografické operace. |
| virtual void [set_FeedbackSize](./set_feedbacksize/)(int) | Nastaví velikost zpětné vazby kryptografické operace. |
| virtual void [set_IV](./set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Nastaví počáteční hodnotu kryptografické operace. |
| virtual void [set_Key](./set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Nastaví klíč kryptografické operace. |
| virtual void [set_KeySize](./set_keysize/)(int) | Nastaví velikost klíče kryptografické operace. |
| virtual void [set_Mode](./set_mode/)([CipherMode](../ciphermode/)) | Nastaví režim kryptografické operace. |
| virtual void [set_Padding](./set_padding/)([PaddingMode](../paddingmode/)) | Nastaví výplň kryptografické operace. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počitadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# lock(). Zavolejte přímo nebo použijte objekt hlídače [LockContext](../../system/lockcontext/). |
| **bool** [ValidKeySize](./validkeysize/)(int) | Kontroluje, zda je velikost klíče platná. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [System::Security::Cryptography](../)
* Knihovna [Aspose.Slides](../../)