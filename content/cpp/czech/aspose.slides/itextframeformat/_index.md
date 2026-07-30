---
title: ITextFrameFormat
second_title: Aspose.Slides pro C++ referenční příručka API
description: Obsahuje formátovací vlastnosti TextFrame.
type: docs
weight: 4083
url: /cs/aspose.slides/itextframeformat/
---
## ITextFrameFormat třída

Obsahuje formátovací vlastnosti [TextFrame](../textframe/).

```cpp
class ITextFrameFormat : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) semantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 není NaN rovno žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual [TextAnchorType](../textanchortype/) [get_AnchoringType](./get_anchoringtype/)() | Vrací text svislého kotvení v [TextFrame](../textframe/). Číst [TextAnchorType](../textanchortype/). |
| virtual [TextAutofitType](../textautofittype/) [get_AutofitType](./get_autofittype/)() | Vrací režim automatického přizpůsobení textu. Číst [TextAutofitType](../textautofittype/). |
| virtual [NullableBool](../nullablebool/) [get_CenterText](./get_centertext/)() | Pokud [NullableBool::True](../nullablebool/), měl by být text vodorovně vycentrován v rámečku. Číst [NullableBool](../nullablebool/). |
| virtual **int32_t** [get_ColumnCount](./get_columncount/)() | Vrací počet sloupců v textové oblasti. Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Číst **int32_t**. |
| virtual **double** [get_ColumnSpacing](./get_columnspacing/)() | Vrací mezery mezi textovými sloupci v textové oblasti (v bodech). Toto by se mělo použít jen když je více než 1 sloupec. Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Číst **double**. |
| virtual **bool** [get_KeepTextFlat](./get_keeptextflat/)() | Vrací nebo nastavuje, že text je zcela mimo 3D scénu. Číst **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | Vrací spodní okraj (v bodech) v [TextFrame](../textframe/). Číst **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | Vrací levý okraj (v bodech) v [TextFrame](../textframe/). Číst **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | Vrací pravý okraj (v bodech) v [TextFrame](../textframe/). Číst **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | Vrací horní okraj (v bodech) v [TextFrame](../textframe/). Číst **double**. |
| virtual **float** [get_RotationAngle](./get_rotationangle/)() | Určuje vlastní rotaci, která se aplikuje na text uvnitř ohraničujícího rámečku. Pokud není specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, je aplikována nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Číst **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_TextStyle](./get_textstyle/)() | Vrací styl textu. Pouze pro čtení [ITextStyle](../itextstyle/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a vlastního úhlu ve vlastnosti RotationAngle. Číst [Slides::TextVerticalType](../textverticaltype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | Vrací objekt [ThreeDFormat](../threedformat/), který představuje 3D efektové vlastnosti pro text. Pouze pro čtení [IThreeDFormat](../ithreedformat/). |
| virtual [TextShapeType](../textshapetype/) [get_Transform](./get_transform/)() | Získává tvar zalamování textu. Číst [TextShapeType](../textshapetype/). |
| virtual [NullableBool](../nullablebool/) [get_WrapText](./get_wraptext/)() | **True** pokud je text zalamován na okrajích [TextFrame](../textframe/). Číst [NullableBool](../nullablebool/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získává datovou strukturu počitadla odkazů spojenou s objektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormatEffectiveData](../itextframeformateffectivedata/)\> [GetEffective](./geteffective/)() | Získává efektivní data formátování textového rámce s aplikovaným děděním. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog metody C# [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získává skutečný typ objektu. Analog volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontroluje, zda objekt představuje instanci typu popsaného targetType. Analog operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání C# lock() prohlášení. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog metody C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytváří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Ve skutečnosti nic nekopíruje, jen inicializuje nový objekt a umožňuje kopírování podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle odkazu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle odkazu. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Snižuje počitadlo sdílených odkazů o zadanou hodnotu. |
| virtual void [set_AnchoringType](./set_anchoringtype/)([TextAnchorType](../textanchortype/)) | Nastavuje text svislého kotvení v [TextFrame](../textframe/). Zapisovat [TextAnchorType](../textanchortype/). |
| virtual void [set_AutofitType](./set_autofittype/)([TextAutofitType](../textautofittype/)) | Nastavuje režim automatického přizpůsobení textu. Zapisovat [TextAutofitType](../textautofittype/). |
| virtual void [set_CenterText](./set_centertext/)([NullableBool](../nullablebool/)) | Pokud [NullableBool::True](../nullablebool/), má být text vodorovně vycentrován v rámečku. Zapisovat [NullableBool](../nullablebool/). |
| virtual void [set_ColumnCount](./set_columncount/)(**int32_t**) | Nastavuje počet sloupců v textové oblasti. Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Zapisovat **int32_t**. |
| virtual void [set_ColumnSpacing](./set_columnspacing/)(**double**) | Nastavuje mezeru mezi textovými sloupci v textové oblasti (v bodech). Toto by se mělo použít jen když je více než 1 sloupec. Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Zapisovat **double**. |
| virtual void [set_KeepTextFlat](./set_keeptextflat/)(**bool**) | Vrací nebo nastavuje, že text je zcela mimo 3D scénu. Zapisovat **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | Nastavuje spodní okraj (v bodech) v [TextFrame](../textframe/). Zapisovat **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | Nastavuje levý okraj (v bodech) v [TextFrame](../textframe/). Zapisovat **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | Nastavuje pravý okraj (v bodech) v [TextFrame](../textframe/). Zapisovat **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | Nastavuje horní okraj (v bodech) v [TextFrame](../textframe/). Zapisovat **double**. |
| virtual void [set_RotationAngle](./set_rotationangle/)(**float**) | Určuje vlastní rotaci, která se aplikuje na text uvnitř ohraničujícího rámečku. Pokud není specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, je aplikována nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Zapisovat **float**. |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a vlastního úhlu ve vlastnosti RotationAngle. Zapisovat [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [set_Transform](./set_transform/)([TextShapeType](../textshapetype/)) | Nastavuje tvar zalamování textu. Zapisovat [TextShapeType](../textshapetype/). |
| virtual void [set_WrapText](./set_wraptext/)([NullableBool](../nullablebool/)) | **True** pokud je text zalamován na okrajích [TextFrame](../textframe/). Zapisovat [NullableBool](../nullablebool/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n-tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získává aktuální hodnotu počitadla sdílených odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvyšuje počitadlo sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Snižuje a vrací počitadlo sdílených odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog metody C# [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemykání C# lock() prohlášení. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvyšuje počitadlo slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Snižuje počitadlo slabých odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Ničí objekt. Uvolňuje všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)