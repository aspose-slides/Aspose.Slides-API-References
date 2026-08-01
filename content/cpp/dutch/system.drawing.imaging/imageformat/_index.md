---
title: ImageFormat
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt het bestandsformaat van een afbeelding voor. Objecten van deze klasse mogen alleen worden gealloceerd met de System::MakeObject() functie. Maak nooit een instantie van dit type op de stack of met operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een System::SmartPtr pointer en gebruik deze pointer om deze door te geven aan functies als argument."
type: docs
weight: 131
url: /nl/system.drawing.imaging/imageformat/
---
## ImageFormat klasse


Stelt het bestandsformaat van een afbeelding voor. Objecten van deze klasse mogen alleen worden toegewezen met behulp van de [System::MakeObject()](../../system/makeobject/) functie. Maak nooit een instantie van dit type op de stack of met de operator new, omdat dit zal leiden tot runtime-fouten en/of assertiefouten. Wikkel deze klasse altijd in een [System::SmartPtr](../../system/smartptr/) pointer en gebruik deze pointer om deze door te geven aan functies als argument.

```cpp
class ImageFormat : public System::Object
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Bepaalt of de afbeeldingsformaten die door het huidige en het opgegeven object worden vertegenwoordigd gelijk zijn. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert C#-stijl zwevend-kommagetallenvergelijking waarbij twee NaN-waarden als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het bitmap-afbeeldingsformaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het enhanced metafile-formaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het Exchangeable [Image](../../system.drawing/image/) File (Exif)-formaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het [Graphics](../../system.drawing/graphics/) Interchange Format (GIF)-afbeeldingsformaat vertegenwoordigt. |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Retourneert de GUID die is gekoppeld aan het afbeeldingsformaat dat door het huidige object wordt vertegenwoordigd. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het [Windows](../../system.windows/)-icoon-afbeeldingsformaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het Joint Photographic Experts Group (JPEG)-afbeeldingsformaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het formaat van een bitmap in het geheugen vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG)-afbeeldingsformaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het Tagged [Image](../../system.drawing/image/) File Format (TIFF)-afbeeldingsformaat vertegenwoordigt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | Retourneert een shared pointer naar een [ImageFormat](./) object dat het [Windows](../../system.windows/) metafile (WMF)-afbeeldingsformaat vertegenwoordigt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller-datastructuur op die aan het object is gekoppeld. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog van de C# [Object.GetHashCode()](../../system/object/gethashcode/) methode. Maakt hashen van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het werkelijke type van het object op. Analog van een C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | Construeert een instantie van de [ImageFormat](./) klasse die een afbeeldingsformaat vertegenwoordigt dat is gekoppeld aan de opgegeven GUID. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van het type vertegenwoordigt dat wordt beschreven door targetType. Analog van de C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implementeert het lock()-statement van C# voor vergrendeling. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachtobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog van de C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) methode. Maakt klonen van aangepaste types mogelijk. |
| [Object](../../system/object/object/)() | Creëert een object. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert slechts een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignatie-operator. Kopieert niets echt, initialiseert slechts een nieuw object en maakt copy-constructie van subklassen mogelijk. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten op referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een value-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de shared referentieteller met de opgegeven waarde. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th sjabloonargument in als een weak pointer (in plaats van shared). Maakt het mogelijk om pointers in containers naar weak-modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de shared referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de shared referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de shared referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Converteert dit [ImageFormat](./) object naar een menselijk leesbare string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert de C# typeof([System.Object](../../system/object/)) constructie. |
| void [Unlock](../../system/object/unlock/)() | Implementeert het unlocken van het C# lock()-statement. Roep direct aan of gebruik het [LockContext](../../system/lockcontext/) wachtobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak referentieteller. Mag niet direct worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt het object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Bibliotheek [Aspose.Slides](../../)