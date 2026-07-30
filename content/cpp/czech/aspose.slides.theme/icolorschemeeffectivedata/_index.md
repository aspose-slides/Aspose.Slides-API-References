---
title: IColorSchemeEffectiveData
second_title: Aspose.Slides pro C++ – API reference
description: Neměnný objekt, který obsahuje efektivní vlastnosti barevného schématu.
type: docs
weight: 157
url: /cs/aspose.slides.theme/icolorschemeeffectivedata/
---
## IColorSchemeEffectiveData třída


Neměnný objekt, který obsahuje efektivní vlastnosti barevného schématu.

```cpp
class IColorSchemeEffectiveData : public virtual System::Object
```

## Metody

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Porovnává objekty pomocí C# [Object.Equals](../../system/object/equals/) sémantiky. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu reference ve stylu C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Porovnává objekty typu hodnota ve stylu C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuluje porovnání plovoucího bodu ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuluje porovnání plovoucího bodu ve stylu C#, kde jsou dva NaN považovány za rovné, i když podle IEC 60559:1989 NaN není roven žádné hodnotě, včetně NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Pouze pro interní použití. |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent1](./get_accent1/)() | První akcentová barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent2](./get_accent2/)() | Druhá akcentová barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent3](./get_accent3/)() | Třetí akcentová barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent4](./get_accent4/)() | Čtvrtá akcentová barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent5](./get_accent5/)() | Pátá akcentová barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Accent6](./get_accent6/)() | Šestá akcentová barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark1](./get_dark1/)() | První tmavá barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Dark2](./get_dark2/)() | Druhá tmavá barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_FollowedHyperlink](./get_followedhyperlink/)() | Barva navštívených hypertextových odkazů. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Hyperlink](./get_hyperlink/)() | Barva hypertextových odkazů. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light1](./get_light1/)() | První světlá barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Light2](./get_light2/)() | Druhá světlá barva ve schématu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Získá datovou strukturu počítadla odkazů spojenou s objektem. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogie C# [Object.GetHashCode()](../../system/object/gethashcode/) metody. Umožňuje hašování vlastních objektů. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Získá skutečný typ objektu. Analogie volání C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual [System::Drawing::Color](../../system.drawing/color/) [idx_get](./idx_get/)([ColorSchemeIndex](../../aspose.slides/colorschemeindex/)) | Získá prvek na zadaném indexu. Pouze pro čtení [System::Drawing::Color](../../system.drawing/color/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Zkontroluje, zda objekt představuje instanci typu popsaného targetType. Analogie operátoru C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementuje zamykání podle C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogie C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metody. Umožňuje klonování vlastních typů. |
|  [Object](../../system/object/object/)() | Vytvoří objekt. Inicializuje všechny vnitřní datové struktury. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopírovací konstruktor. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operátor přiřazení. Vlastně nic nekopíruje, pouze inicializuje nový objekt a umožňuje konstrukci podtříd kopií. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Porovnává objekty podle reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Porovnává referenci hodnotového typu s nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězce a nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specializace [Object::ReferenceEquals](../../system/object/referenceequals/) pro případ řetězců. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Sníží sdílený čítač odkazů o zadanou hodnotu. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Nastaví n'tý šablonový argument na slabý ukazatel (namísto sdíleného). Umožňuje přepnout ukazatele v kontejnerech do slabého režimu. |
| int [SharedCount](../../system/object/sharedcount/)() const | Získá aktuální hodnotu sdíleného čítače odkazů. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Zvětší sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Zmenší a vrátí sdílený čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogie C# [Object.ToString()](../../system/object/tostring/) metody. Umožňuje převod vlastních objektů na řetězec. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementuje konstrukci C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementuje odemčení podle C# lock(). Zavolejte přímo nebo použijte objekt strážce [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zvětší slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zmenší slabý čítač odkazů. Nemělo by se volat přímo; místo toho použijte chytré ukazatele nebo ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Zničí objekt. Uvolní všechny vnitřní datové struktury. |
## Poznámky


Tato třída se používá jako součást [IThemeEffectiveData](../ithemeeffectivedata/). 
## Viz také

* Třída [Object](../../system/object/)
* Jmenný prostor [Aspose::Slides::Theme](../)
* Knihovna [Aspose.Slides](../../)