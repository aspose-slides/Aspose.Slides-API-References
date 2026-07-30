---
title: LayoutPlaceholderManager
second_title: Aspose.Slides pro C++ referenční příručka API
description: Představuje správce, který vám umožňuje přidávat zástupné objekty do snímku rozvržení.
type: docs
weight: 4278
url: /cs/aspose.slides/layoutplaceholdermanager/
---
## LayoutPlaceholderManager třída


Představuje správce, který vám umožňuje přidávat zástupné objekty do snímku rozvržení.

```cpp
class LayoutPlaceholderManager : public Aspose::Slides::ILayoutPlaceholderManager
```

## Metody

| Metoda | Popis |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddChartPlaceholder](./addchartplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval graf. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddContentPlaceholder](./addcontentplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obsah, například obrázek, tabulku, média nebo text. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddMediaPlaceholder](./addmediaplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval mediální objekt. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddOnlineImagePlaceholder](./addonlineimageplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval online obrázek. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddPicturePlaceholder](./addpictureplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obrázek. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddSmartArtPlaceholder](./addsmartartplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval diagram [SmartArt](../../aspose.slides.smartart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTablePlaceholder](./addtableplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval tabulku. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddTextPlaceholder](./addtextplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval textový obsah. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalContentPlaceholder](./addverticalcontentplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval obsah, například obrázek, tabulku, média nebo text ve svislém směru. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShape](../iautoshape/)\> [AddVerticalTextPlaceholder](./addverticaltextplaceholder/)(**float**, **float**, **float**, **float**) override | Přidá nový tvar zástupného objektu do snímku rozvržení, aby obsahoval textový obsah ve svislém směru. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považována za rovná, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dvě NaN považována za rovná, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů přidruženou k objektu. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie C# [System.Object.GetType()](../../system/object/gettype/) volání. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného pomocí targetType. Analogie C# operátoru 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nekopíruje nic, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nekopíruje nic, jen inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává objekt typu hodnota s nullptr pomocí reference. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý argument šablony na slabý ukazatel (namísto sdíleného). Umožňuje přepínat ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje C# konstrukci typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odblokování pomocí C# lock() příkazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |
## Viz také

* Třída [ILayoutPlaceholderManager](../ilayoutplaceholdermanager/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)