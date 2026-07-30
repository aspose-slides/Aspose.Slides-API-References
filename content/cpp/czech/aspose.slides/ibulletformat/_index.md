---
title: IBulletFormat
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Reprezentuje vlastnosti formátování odrážek odstavce.
type: docs
weight: 1561
url: /cs/aspose.slides/ibulletformat/
---
## IBulletFormat třída

Reprezentuje vlastnosti formátování odrážek odstavce.

```cpp
class IBulletFormat : public virtual System::Object
```

## Metody

| Metoda | Popis |
| --- | --- |
| virtual void [ApplyDefaultParagraphIndentsShifts](./applydefaultparagraphindentsshifts/)() | Nastavuje výchozí ne-nulové posuny pro efektivní odstavcové Indent a MarginLeft, když jsou odrážky povoleny (jako PowerPoint dělá, pokud povolíte odrážky/číslování v odstavci). Pokud jsou odrážky zakázány, pouze resetuje Indent a MarginLeft odstavce (jako PowerPoint dělá, pokud zakážete odrážky/číslování v odstavci). Posuny odrážek jsou aplikovány s ohledem na aktuální kontext odrážky – IBulletFormat::get(set)_Type, .NumberedBulletStyle a FontHeight první části. Ne-nulové posuny odrážek jsou aplikovány na efektivní Indent a MarginLeft aktuálního odstavce (aby výsledné hodnoty byly lokální). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty referenčního typu ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty hodnotového typu ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání s plovoucí desetinnou čárkou ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání s dvojitou přesností ve stylu C#, kde jsou dva NaN považovány za stejné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní účely. |
| virtual char16_t [get_Char](./get_char/)() | Vrací znak odrážky odstavce bez dědičnosti. Číst **wchar_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\> [get_Color](./get_color/)() | Vrací formát barvy odrážky odstavce bez dědičnosti. Pouze pro čtení [IColorFormat](../icolorformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\> [get_Font](./get_font/)() | Vrací písmo odrážky odstavce bez dědičnosti. Číst [IFontData](../ifontdata/). |
| virtual **float** [get_Height](./get_height/)() | Vrací výšku odrážky odstavce bez dědičnosti. Hodnota std::numeric_limits<float>::quiet_NaN() určuje, že odrážka dědí výšku z první části odstavce. Číst **float**. |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardColor](./get_isbullethardcolor/)() | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. **[NullableBool::True](../nullablebool/)**, pokud odrážka má vlastní barvu, a **[NullableBool::False](../nullablebool/)**, pokud odrážka dědí barvu z první části odstavce. Číst [NullableBool](../nullablebool/). |
| virtual [NullableBool](../nullablebool/) [get_IsBulletHardFont](./get_isbullethardfont/)() | Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. **[NullableBool::True](../nullablebool/)**, pokud odrážka má vlastní písmo, a **[NullableBool::False](../nullablebool/)**, pokud odrážka dědí písmo z první části odstavce. Číst [NullableBool](../nullablebool/). |
| virtual **int16_t** [get_NumberedBulletStartWith](./get_numberedbulletstartwith/)() | Vrací první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. Číst **int16_t**. |
| virtual [Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/) [get_NumberedBulletStyle](./get_numberedbulletstyle/)() | Vrací styl číslované odrážky bez dědičnosti. Číst [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Vrací obrázek použitý jako odrážka v odstavci bez dědičnosti. Pouze pro čtení [ISlidesPicture](../islidespicture/). |
| virtual [BulletType](../bullettype/) [get_Type](./get_type/)() | Vrací typ odrážky odstavce bez dědičnosti. Číst [BulletType](../bullettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla referencí spojenou s objektem. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormatEffectiveData](../ibulletformateffectivedata/)\> [GetEffective](./geteffective/)() | Získá efektivní data formátování odrážky s aplikovanou dědičností. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# metody [Object.GetHashCode()](../../system/object/gethashcode/). Umožňuje hashování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá aktuální typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání dle C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# metody [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje kopírovací konstrukci podtříd. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referencí objekt hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač referencí o zadanou hodnotu. |
| virtual void [set_Char](./set_char/)(char16_t) | Nastavuje znak odrážky odstavce bez dědičnosti. Zapsat **wchar_t**. |
| virtual void [set_Font](./set_font/)([System::SharedPtr](../../system/sharedptr/)\<[IFontData](../ifontdata/)\>) | Nastavuje písmo odrážky odstavce bez dědičnosti. Zapsat [IFontData](../ifontdata/). |
| virtual void [set_Height](./set_height/)(**float**) | Nastavuje výšku odrážky odstavce bez dědičnosti. Hodnota std::numeric_limits<float>::quiet_NaN() určuje, že odrážka dědí výšku z první části odstavce. Zapsat **float**. |
| virtual void [set_IsBulletHardColor](./set_isbullethardcolor/)([NullableBool](../nullablebool/)) | Určuje, zda má odrážka vlastní barvu nebo ji dědí z první části odstavce. **[NullableBool::True](../nullablebool/)**, pokud odrážka má vlastní barvu, a **[NullableBool::False](../nullablebool/)**, pokud odrážka dědí barvu z první části odstavce. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_IsBulletHardFont](./set_isbullethardfont/)([NullableBool](../nullablebool/)) | Určuje, zda má odrážka vlastní písmo nebo je děděno z první části odstavce. **[NullableBool::True](../nullablebool/)**, pokud odrážka má vlastní písmo, a **[NullableBool::False](../nullablebool/)**, pokud odrážka dědí písmo z první části odstavce. Zapsat [NullableBool](../nullablebool/). |
| virtual void [set_NumberedBulletStartWith](./set_numberedbulletstartwith/)(**int16_t**) | Nastavuje první číslo, které se používá pro skupinu číslovaných odrážek bez dědičnosti. Zapsat **int16_t**. |
| virtual void [set_NumberedBulletStyle](./set_numberedbulletstyle/)([Aspose::Slides::NumberedBulletStyle](../numberedbulletstyle/)) | Nastavuje styl číslované odrážky bez dědičnosti. Zapsat [NumberedBulletStyle](../numberedbulletstyle/). |
| virtual void [set_Type](./set_type/)([BulletType](../bullettype/)) | Nastavuje typ odrážky odstavce bez dědičnosti. Zapsat [BulletType](../bullettype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument jako slabý ukazatel (namísto sdíleného). Umožňuje přepínání ukazatelů v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače referencí. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Sníží a vrátí sdílený čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# metody [Object.ToString()](../../system/object/tostring/). Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemknutí C# lock() výrazu. Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvýší slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Sníží slabý čítač referencí. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |

## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides](../)
* Knihovna [Aspose.Slides](../../)