---
title: ECDsa
second_title: Aspose.Slides pro C++ – reference API
description: "Základní třída pro implementace algoritmu ECDsa. Objekty této třídy by měly být alokovány pouze pomocí funkce System::MakeObject(). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel k předání do funkcí jako argument."
type: docs
weight: 183
url: /cs/system.security.cryptography/ecdsa/
---
## ECDsa třída


Základní třída pro implementace algoritmu [ECDsa](./). Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../../system/smartptr/) a použijte tento ukazatel k předání do funkcí jako argument.

```cpp
class ECDsa : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [Clear](../asymmetricalgorithm/clear/)() | Uvolní všechny zdroje. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)() | Vytvoří výchozí implementaci algoritmu ECDSA. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECCurve](../eccurve/)\&) | Vytvoří výchozí implementaci algoritmu ECDSA s nově vytvořeným klíčem nad zadanou křivkou. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [ECParameters](../ecparameters/)\&) | Vytvoří výchozí implementaci algoritmu ECDSA pomocí zadaných parametrů. |
| static [SharedPtr](../../system/sharedptr/)\<[ECDsa](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Vytvoří specifikovanou implementaci algoritmu ECDSA. |
| void [Dispose](../asymmetricalgorithm/dispose/)() override | Uvolní zdroje vlastněné aktuálním objektem. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovná objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovná objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí řádové čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual [ECParameters](../ecparameters/) [ExportExplicitParameters](./exportexplicitparameters/)(**bool**) | Exportuje explicitní parametry. |
| virtual [ECParameters](../ecparameters/) [ExportParameters](./exportparameters/)(**bool**) | Exportuje pojmenované nebo explicitní parametry. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual void [FromXmlString](../asymmetricalgorithm/fromxmlstring/)([String](../../system/string/)) | Načte parametry algoritmu z XML řetězce. |
| virtual void [GenerateKey](./generatekey/)(const [ECCurve](../eccurve/)\&) | Vygeneruje nový pár veřejného/soukromého klíče pro zadanou křivku. |
| [String](../../system/string/) [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Získá algoritmus výměny klíčů k použití. |
| virtual **int32_t** [get_KeySize](../asymmetricalgorithm/get_keysize/)() | Získá velikost klíče. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[KeySizes](../keysizes/)\>\> [get_LegalKeySizes](../asymmetricalgorithm/get_legalkeysizes/)() | Získá pole povolených velikostí klíčů. |
| [String](../../system/string/) [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Získá algoritmus podpisu k použití. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| virtual void [ImportParameters](./importparameters/)(const [ECParameters](../ecparameters/)\&) | Importuje všechny parametry z datové struktury. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
| [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny interní datové struktury. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovná objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovná referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží počet sdílených odkazů o zadanou hodnotu. |
| virtual void [set_KeySize](../asymmetricalgorithm/set_keysize/)(**int32_t**) | Nastaví velikost klíče. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu počítadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí počet sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [HashAlgorithmName](../hashalgorithmname/)\&) | Vypočítá hash hodnotu zadaného pole dat pomocí zadaného hash algoritmu a podepíše výsledek. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignData](./signdata/)(const [StreamPtr](../../system/streamptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Vypočítá hash hodnotu zadaného binárního proudu pomocí zadaného hash algoritmu a podepíše výsledek. |
| virtual [ByteArrayPtr](../../system/bytearrayptr/) [SignHash](./signhash/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&) | Vypočítá podpis zadané vstupní hodnoty. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| virtual [String](../../system/string/) [ToXmlString](../asymmetricalgorithm/toxmlstring/)(**bool**) | Zapíše parametry algoritmu do XML řetězce. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení příkazu C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ověřuje, že podpis zadaných dat je platný. |
| **bool** [VerifyData](./verifydata/)(const [ByteArrayPtr](../../system/bytearrayptr/)\&, **int32_t**, **int32_t**, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ověřuje, že podpis zadaných dat je platný. |
| **bool** [VerifyData](./verifydata/)(const [StreamPtr](../../system/streamptr/)\&, const [ByteArrayPtr](../../system/bytearrayptr/)\&, const [HashAlgorithmName](../hashalgorithmname/)\&) | Ověřuje, že podpis zadaného binárního proudu je platný. |
| virtual **bool** [VerifyHash](./verifyhash/)([ByteArrayPtr](../../system/bytearrayptr/), [ByteArrayPtr](../../system/bytearrayptr/)) | Kontroluje podpis dat. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží počet slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny interní datové struktury. |

## Viz také

* Třída [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Jmenný prostor [System::Security::Cryptography](../)
* Knihovna [Aspose.Slides](../../)