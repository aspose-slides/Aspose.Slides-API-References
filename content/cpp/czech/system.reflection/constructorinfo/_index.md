---
title: ConstructorInfo
second_title: Aspose.Slides pro C++ referenční příručka API
description: Poskytuje přístup k metadatům konstruktoru.
type: docs
weight: 53
url: /cs/system.reflection/constructorinfo/
---
## ConstructorInfo třída

Poskytuje přístup k metadatům konstruktoru.

```cpp
class ConstructorInfo : public System::Reflection::MethodBase
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | Přidá atribut do kolekce. |
|  [ConstructorInfo](./constructorinfo/)(const [String](../../system/string/)\&, std::function\<[System::Object::ptr](../../system/object/ptr/)()>) | Inicializuje novou instanci třídy [ConstructorInfo](./) pro konstruktor bez parametrů. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](./get_declaringtype/)() | Získá třídu, která deklaruje tento člen. NOT IMPLEMENTED. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | Získá deklarující typ. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | Získá úplný název členu. Může se lišit v ručně implementovaných částech. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | Získá hodnotu MemberTypes označující, že tento člen je konstruktor. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | Získá název členu. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | Získá typ reflektovaného typu. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí přidruženou k objektu. |
| static [System::SharedPtr](../../system/sharedptr/)\<[MemberInfo](../memberinfo/)\> [GetCurrentMethod](../methodbase/getcurrentmethod/)(const [String](../../system/string/)\&) | Tato metoda umožňuje získat aktuální název metody. Překladač automaticky nahrazuje parametr ASPOSE_CURRENT_FUNCTION. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | Vrátí pole obsahující objekty, které představují všechny vlastní atributy aplikované na typ reprezentovaný aktuálním objektem. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | Vrátí pole obsahující objekty, které představují všechny vlastní atributy aplikované na typ reprezentovaný aktuálním objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Invoke](./invoke/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | Vyvolá metodu nebo konstruktor reprezentovaný aktuální instancí pomocí zadaných parametrů. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného parametrem targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [MethodBase](../methodbase/methodbase/)() | Inicializuje novou instanci třídy [MethodBase](../methodbase/). |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvýší sdílený čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokování pomocí C# lock() výrazu. Zavolejte přímo nebo použijte objekt hlídky [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Neměl by být volán přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [MethodBase](../methodbase/)
* Jmenný prostor [System::Reflection](../)
* Knihovna [Aspose.Slides](../../)