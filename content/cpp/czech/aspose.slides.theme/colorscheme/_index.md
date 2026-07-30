---
title: ColorScheme
second_title: Reference API Aspose.Slides pro C++
description: Ukládá barvy definované tématem.
type: docs
weight: 40
url: /cs/aspose.slides.theme/colorscheme/
---
## ColorScheme třída

Stores theme-defined colors.

```cpp
class ColorScheme : public Aspose::Slides::Theme::IColorScheme,
                    public Aspose::Slides::IDOMObject
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí semantiky C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání desetinných čísel ve stylu C#, kde jsou dvě NaN považovány za stejné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Accent1](./get_accent1/)() override | První akcentní barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Accent2](./get_accent2/)() override | Druhá akcentní barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Accent3](./get_accent3/)() override | Třetí akcentní barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Accent4](./get_accent4/)() override | Čtvrtá akcentní barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Accent5](./get_accent5/)() override | Pátá akcentní barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Accent6](./get_accent6/)() override | Šestá akcentní barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Dark1](./get_dark1/)() override | První tmavá barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Dark2](./get_dark2/)() override | Druhá tmavá barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_FollowedHyperlink](./get_followedhyperlink/)() override | Barva pro navštívené hypertextové odkazy. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Hyperlink](./get_hyperlink/)() override | Barva pro hypertextové odkazy. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Light1](./get_light1/)() override | První světlá barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_Light2](./get_light2/)() override | Druhá světlá barva ve schématu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](./get_presentation/)() override | Vrací nadřazenou prezentaci. Pouze pro čtení [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](./get_slide/)() override | Vrací nadřazený snímek. Pouze pro čtení [IBaseSlide](../../aspose.slides/ibaseslide/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [idx_get](./idx_get/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) override | Získá prvek na zadaném indexu. Pouze pro čtení [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí výrazu C# lock(). Volá se přímo nebo pomocí objektu [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci odvozených tříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci odvozených tříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený počítadlo referencí o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony jako slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného počítadla referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílené počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení pomocí výrazu C# lock(). Volá se přímo nebo pomocí objektu [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabé počítadlo referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [IColorScheme](../icolorscheme/)
* Třída [IDOMObject](../../aspose.slides/idomobject/)
* Jmenný prostor [Aspose::Slides::Theme](../)
* Knihovna [Aspose.Slides](../../)