---
title: EnumConverter
second_title: "Aspose.Slides pro C++ referenční příručka API"
description: "Fiktivní třída pro použití EnumConverter při překladu přeloženého kódu, aby bylo možné jej zkompilovat. Objektům této třídy by mělo být přidělováno pouze pomocí funkce System::MakeObject(). Nikdy neinstanciujte tento typ na zásobníku ani pomocí operátoru new, protože to povede k chybám za běhu a/nebo k selháním asercí. Vždy zabalte tuto třídu do ukazatele System::SmartPtr a použijte tento ukazatel jako argument při předávání funkcím."
type: docs
weight: 105
url: /cs/system.componentmodel/enumconverter/
---
## EnumConverter třída

Dummy class for EnumConverter-using translated code to compile. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class EnumConverter : public System::ComponentModel::TypeConverter
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [CanConvertFrom](./canconvertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Kontroluje, zda jsou typy převoditelné; není implementováno. |
| **bool** [CanConvertTo](./canconvertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Kontroluje, zda jsou typy převoditelné; není implementováno. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](./convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) override | Provádí skutečný převod typu; není implementováno. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Převádí objekty. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFrom](../typeconverter/convertfrom/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Převádí řetězec na objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../typeconverter/convertfrominvariantstring/)(const [System::String](../../system/string/)\&) | Převádí invariantní řetězec na objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromInvariantString](../typeconverter/convertfrominvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Převádí invariantní řetězec na objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::String](../../system/string/)\&) | Převádí řetězec na objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::String](../../system/string/)\&) | Převádí řetězec na objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertFromString](../typeconverter/convertfromstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::String](../../system/string/)\&) | Převádí řetězec na objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](./convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) override | Provádí skutečný převod typu; není implementováno. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [ConvertTo](../typeconverter/convertto/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::TypeInfo](../../system/typeinfo/)\&) | Převádí objekt na konkrétní typ. |
| [System::String](../../system/string/) [ConvertToInvariantString](../typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Převádí objekt na invariantní řetězec. |
| [System::String](../../system/string/) [ConvertToInvariantString](../typeconverter/converttoinvariantstring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Převádí objekt na invariantní řetězec. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Převádí objekt na řetězec. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Převádí objekt na řetězec. |
| [System::String](../../system/string/) [ConvertToString](../typeconverter/converttostring/)(const [System::SharedPtr](../../system/sharedptr/)\<[ITypeDescriptorContext](../itypedescriptorcontext/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | Převádí objekt na řetězec. |
|  [EnumConverter](./enumconverter/)(const [System::TypeInfo](../../system/typeinfo/)\&) | Informace RTTI. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí sémantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnot ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| const [System::TypeInfo](../../system/typeinfo/)\& [get_EnumType](./get_enumtype/)() | Získá typ výčtu, se kterým [EnumConverter](./) pracuje; není implementováno. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt typu hodnoty s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
|  [TypeConverter](../typeconverter/typeconverter/)() | Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho používejte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [TypeConverter](../typeconverter/)
* Jmenný prostor [System::ComponentModel](../)
* Knihovna [Aspose.Slides](../../)