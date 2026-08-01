---
title: PPImage
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een afbeelding in een presentatie voor.
type: docs
weight: 4824
url: /nl/aspose.slides/ppimage/
---
## PPImage klasse


Stelt een afbeelding in een presentatie voor.

```cpp
class PPImage : public Aspose::Slides::IPPImage,
                public System::IDisposable
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Dispose](./dispose/)() override | Verwijdert object. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met behulp van C# [Object.Equals](../../system/object/equals/)-semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentietype-objecten in C#-stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waardetype-objecten in C#-stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Imiteert C#-stijl zwevend-komma vergelijking waarbij twee NaN's als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan enige waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor interne doeleinden. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_BinaryData](./get_binarydata/)() override | Retourneert een kopie van de gegevens van een afbeelding. Alleen-lezen **uint8_t**[]. |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Retourneert een MIME-type van een afbeelding, gecodeerd in [PPImage::get_BinaryData](./get_binarydata/). Alleen-lezen [System::String](../../system/string/). |
| **int32_t** [get_Height](./get_height/)() override | Retourneert een hoogte van een afbeelding. Alleen-lezen **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\> [get_Image](./get_image/)() override | Retourneert een kopie van een afbeelding. Alleen-lezen [IImage](../iimage/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\> [get_SvgImage](./get_svgimage/)() const override | Retourneert [ISvgImage](../isvgimage/) object [ISvgImage](../isvgimage/) |
| **int32_t** [get_Width](./get_width/)() override | Retourneert een breedte van een afbeelding. Alleen-lezen **int32_t**. |
| **int32_t** [get_X](./get_x/)() override | Retourneert een X-offset van een afbeelding. Alleen-lezen **int32_t**. |
| **int32_t** [get_Y](./get_y/)() override | Retourneert een Y-offset van een afbeelding. Alleen-lezen **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt referentieteller-datastructuur op die bij het object hoort. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Retourneert de hashcode van een afbeelding. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge van C# [System.Object.GetType()](../../system/object/gettype/)-aanroep. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie van een type vertegenwoordigt zoals beschreven door targetType. Analoge van C# 'is'-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement vergrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge van C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Stelt klonen van aangepaste types in stand. |
| [Object](../../system/object/object/)() | Maakt object aan. Initialiseert alle interne datastructuren. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopiëringsconstructor. Kopieert niets echt, initialiseert alleen een nieuw object en stelt het kopiëren van subklassen in staat. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Toewijzingsoperator. Kopieert niets echt, initialiseert alleen een nieuw object en stelt het kopiëren van subklassen in staat. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waardetype-object per referentie met nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval van strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Vermindert de gedeelde referentieteller met de opgegeven waarde. |
| void [ReplaceImage](./replaceimage/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Vervangt afbeeldingsgegevens. |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IImage](../iimage/)\>) override | Vervangt afbeeldingsgegevens. Let op: wanneer Image een metafile is – deze wordt gerasterd. Gebruik ReplaceImage(byte[]) in plaats daarvan. |
| void [ReplaceImage](./replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::IPPImage](../ippimage/)\>) override | Vervangt afbeeldingsgegevens. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>) | Vervangt afbeelding. |
| virtual void [ReplaceImage](../ippimage/replaceimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | Vervangt afbeelding. |
| void [set_SvgImage](./set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::ISvgImage](../isvgimage/)\>) override | Stelt [ISvgImage](../isvgimage/) object [ISvgImage](../isvgimage/) in. |
| virtual void [set_SvgImage](../ippimage/set_svgimage/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgImage](../isvgimage/)\>) | Stelt [ISvgImage](../isvgimage/) object [ISvgImage](../isvgimage/) in. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt n'th template-argument in op een zwakke pointer (in plaats van gedeelde). Staat toe om pointers in containers naar zwakke modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt en retourneert de gedeelde referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analoge van C# [Object.ToString()](../../system/object/tostring/)-methode. Stelt het converteren van aangepaste objecten naar string in stand. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement ontgrendeling. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de zwakke referentieteller. Moet niet direct worden aangeroepen; gebruik in plaats daarvan slimme pointers of ThisProtector. |
| virtual [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |

## Zie ook

* Klasse [IPPImage](../ippimage/)
* Klasse [IDisposable](../../system/idisposable/)
* Namespace [Aspose::Slides](../)
* Bibliotheek [Aspose.Slides](../../)