---
title: Control
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje ActiveX ovládací prvek.
type: docs
weight: 508
url: /cs/aspose.slides/control/
---
## Control třída

Reprezentuje ActiveX ovládací prvek.

```cpp
class Control : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::ControlCollection>>,
                public Aspose::Slides::IControl
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucí desetinné čárky ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_ActiveXControlBinary](./get_activexcontrolbinary/)() override | Určuje perzistenci ActiveX ovládacího prvku, když je metoda pro uložení buď PersistStream, PersistStreamInit nebo PersistStorage. |
| [System::Guid](../../system/guid/) [get_ClassId](./get_classid/)() override | Získává ID třídy tohoto ovládacího prvku. Pouze ke čtení [System::Guid](../../system/guid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | Vrací rámec ovládacího prvku. Čtení [IShapeFrame](../ishapeframe/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | Získává název tohoto ovládacího prvku. Čtení [System::String](../../system/string/). |
| [PersistenceType](../persistencetype/) [get_Persistence](./get_persistence/)() override | Získává metodu používanou k uložení vlastností ActiveX ovládacího prvku. Pouze ke čtení [PersistenceType](../persistencetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlPropertiesCollection](../icontrolpropertiescollection/)\> [get_Properties](./get_properties/)() override | Vrací kolekci vlastností ActiveX. |
| [System::String](../../system/string/) [get_Property](./get_property/)([System::String](../../system/string/)) override | Vrací vlastnost ActiveX na zadaném indexu. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | Vrací objekt vlastností výplně obrázku [Control](./). Pouze ke čtení [IPictureFillFormat](../ipicturefillformat/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává aktuální typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání příkazem C# lock(). Zavolejte přímo nebo použijte objekt hlídače [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje sdílený čítač referencí o zadanou hodnotu. |
| void [set_ClassId](./set_classid/)([System::Guid](../../system/guid/)) | Získává ID třídy tohoto ovládacího prvku. Pouze ke čtení [System::Guid](../../system/guid/). |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | Nastavuje rámec ovládacího prvku. Zapisuje [IShapeFrame](../ishapeframe/). |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | Nastavuje název tohoto ovládacího prvku. Zapisuje [System::String](../../system/string/). |
| void [set_Property](./set_property/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Nastaví vlastnost ActiveX na zadaném indexu. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepnutí ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí příkazem C# lock(). Zavolejte přímo nebo použijte objekt hlídače [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Niči objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [DomObject](../domobject/)
* Třída [IControl](../icontrol/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)