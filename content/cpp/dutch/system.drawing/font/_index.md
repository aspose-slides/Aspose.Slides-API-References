---
title: Font
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een specifiek formaat voor tekst voor, inclusief lettertype, grootte en stijl. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om het aan functies als argument door te geven."
type: docs
weight: 79
url: /nl/system.drawing/font/
---
## Fontklasse

Representeert een specifiek formaat voor tekst, inclusief lettertype, grootte en stijl. Objecten van deze klasse mogen alleen worden gealloceerd met de [System::MakeObject()](../../system/makeobject/)-functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit leidt tot runtime-fouten en/of assertiefouten. Wrap deze klasse altijd in een [System::SmartPtr](../../system/smartptr/)-pointer en gebruik deze pointer om het aan functies als argument door te geven.

```cpp
class Font : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | Retourneert een kopie van het huidige lettertype. |
| void [Dispose](./dispose/)() | Vrijgeeft alle door het besturingssysteem verkregen bronnen die door het huidige object zijn verworven. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bepaalt of het huidige en het opgegeven object identiek zijn. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevendekommagetallen vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | Construeert een nieuw exemplaar van de [Font](./) klasse die het opgegeven bestaande lettertype weergeeft met de opgegeven lettertype-stijl. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Construeert een nieuw exemplaar van de [Font](./) klasse. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | Construeert een nieuw exemplaar van de [Font](./) klasse. |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Construeert een nieuw exemplaar van de [Font](./) klasse. |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | Construeert een nieuw exemplaar van de [Font](./) klasse. |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | NIET GEREALISEERD. |
| **bool** [get_Bold](./get_bold/)() | Bepaalt of het door het huidige object weergegeven lettertype de vette stijl heeft toegepast. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | Retourneert de lettertypefamilie van het door het huidige object weergegeven lettertype. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | Retourneert de lettertype-stijl van het door het huidige object weergegeven lettertype. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | Retourneert een waarde die aangeeft welke GDI-tekenset wordt gebruikt door het door het huidige object weergegeven lettertype. |
| int [get_Height](./get_height/)() | Retourneert de regelafstand van het door het huidige object weergegeven lettertype in pixels. |
| **bool** [get_Italic](./get_italic/)() | Bepaalt of het door het huidige object weergegeven lettertype de cursieve stijl heeft toegepast. |
| [String](../../system/string/) [get_Name](./get_name/)() | Retourneert de gezichtsnaam van het door het huidige object weergegeven lettertype. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | Retourneert de oorspronkelijk gespecificeerde naam van het lettertype. |
| **float** [get_Size](./get_size/)() | Retourneert de em-grootte van het door het huidige object weergegeven lettertype gemeten in de eenheden gespecificeerd door de eigenschap Unit. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | Retourneert de em-grootte van het door het huidige object weergegeven lettertype in punten. |
| **bool** [get_Strikeout](./get_strikeout/)() | Bepaalt of het door het huidige object weergegeven lettertype de doorstrepingsstijl heeft toegepast. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | Retourneert de lettertype-stijl van het door het huidige object weergegeven lettertype. |
| **bool** [get_Underline](./get_underline/)() | Bepaalt of het door het huidige object weergegeven lettertype de onderstreepte stijl heeft toegepast. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | Retourneert de meeteenheid voor het door het huidige object weergegeven lettertype. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die bij het object hoort. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoge aan de C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt het hashen van aangepaste objecten mogelijk. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Retourneert de regelafstand van het door het huidige object weergegeven lettertype, in de huidige eenheid van een gespecificeerd [Graphics](../graphics/)-object. |
| **float** [GetHeight](./getheight/)(**float**) | Retourneert de hoogte van het door het huidige object weergegeven lettertype wanneer getekend op een weergaveapparaat met de gespecificeerde verticale resolutie. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge aan de C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleer of het object een exemplaar is van het type beschreven door targetType. Analoge aan de C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het blokkeren van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt het klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-constructor. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert eigenlijk niets, initialiseert alleen een nieuw object en maakt het mogelijk subklassen te kopiëren. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-sjabloonargument in op een zwakke pointer (in plaats van gedeeld). Stelt toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge aan de C# [Object.ToString()](../../system/object/tostring/)-methode. Maakt het converteren van aangepaste objecten naar string mogelijk. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het ontgrendelen van de C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Naamruimte [System::Drawing](../)
* Bibliotheek [Aspose.Slides](../../)