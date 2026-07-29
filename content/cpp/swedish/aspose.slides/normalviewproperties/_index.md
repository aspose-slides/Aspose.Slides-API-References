---
title: NormalViewProperties
second_title: Aspose.Slides för C++ API-referens
description: "Representerar normalvyens egenskaper. Normalvyn består av tre innehållsregioner: själva bilden, en sidoinnehållsregion och en botteninnehållsregion."
type: docs
weight: 4525
url: /sv/aspose.slides/normalviewproperties/
---
## NormalViewProperties klass

Representerar normalvyns egenskaper. Normalvyn består av tre innehållsregioner: själva bilden, en sidoinnehållsregion och en botteninnehållsregion.

```cpp
class NormalViewProperties : public Aspose::Slides::INormalViewProperties
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypsobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypsobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_HorizontalBarState](./get_horizontalbarstate/)() override | Anger det tillstånd som den horisontella delningsbaren ska visas i. En horisontell delningsbar separerar bilden från innehållsregionen under bilden. |
| **bool** [get_PreferSingleView](./get_prefersingleview/)() override | Anger om användaren föredrar att se ett helfönster-ensamt innehållsområde istället för standard-normalvyn med tre innehållsregioner. Om aktiverat kan programmet välja att visa en av innehållsregionerna i hela fönstret. Läs **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredLeft](./get_restoredleft/)() override | Detta element anger storleksinställningarna för sidoinnehållsregionen i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maximerad). Endast läs [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INormalViewRestoredProperties](../inormalviewrestoredproperties/)\> [get_RestoredTop](./get_restoredtop/)() override | Detta element anger storleksinställningarna för den övre bildregionen i normalvyn när regionen har en variabel återställd storlek (varken minimerad eller maximerad). Endast läs [INormalViewRestoredProperties](../inormalviewrestoredproperties/). |
| **bool** [get_ShowOutlineIcons](./get_showoutlineicons/)() override | Anger om programmet ska visa ikoner när innehållsöversikt visas i någon av innehållsregionerna i normalvyläge. Läs **bool**. |
| **bool** [get_SnapVerticalSplitter](./get_snapverticalsplitter/)() override | Anger om den vertikala delningsbaren ska låsas till ett minimerat tillstånd när sidoregionen är tillräckligt liten. Läs **bool**. |
| [SplitterBarStateType](../splitterbarstatetype/) [get_VerticalBarState](./get_verticalbarstate/)() override | Anger det tillstånd som den vertikala delningsbaren ska visas i. En vertikal delningsbar separerar bilden från sidoinnehållsregionen. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satset. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför värdetypsobjekt med nullptr efter referens. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| void [set_HorizontalBarState](./set_horizontalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Anger det tillstånd som den horisontella delningsbaren ska visas i. En horisontell delningsbar separerar bilden från innehållsregionen under bilden. |
| void [set_PreferSingleView](./set_prefersingleview/)(**bool**) override | Anger om användaren föredrar att se ett helfönster-ensamt innehållsområde istället för standard-normalvyn med tre innehållsregioner. Om aktiverat kan programmet välja att visa en av innehållsregionerna i hela fönstret. Skriv **bool**. |
| void [set_ShowOutlineIcons](./set_showoutlineicons/)(**bool**) override | Anger om programmet ska visa ikoner när innehållsöversikt visas i någon av innehållsregionerna i normalvyläge. Skriv **bool**. |
| void [set_SnapVerticalSplitter](./set_snapverticalsplitter/)(**bool**) override | Anger om den vertikala delningsbaren ska låsas till ett minimerat tillstånd när sidoregionen är tillräckligt liten. Skriv **bool**. |
| void [set_VerticalBarState](./set_verticalbarstate/)([SplitterBarStateType](../splitterbarstatetype/)) override | Anger det tillstånd som den vertikala delningsbaren ska visas i. En vertikal delningsbar separerar bilden från sidoinnehållsregionen. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n'te mallargument till en svag pekare (snarare än delad). Tillåter byte av pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar upplåsning enligt C# lock()-satset. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Ska inte anropas direkt; använd istället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Anmärkningar

Följande exempel visar hur man konfigurerar [ViewProperties::get_NormalViewProperties](../viewproperties/get_normalviewproperties/)-egenskaper för en PowerPoint [Presentation](../presentation/). 
```cpp
// Instansiera ett presentationsobjekt som representerar en presentationsfil
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
auto normalViewProperties = pres->get_ViewProperties()->get_NormalViewProperties();

normalViewProperties->set_HorizontalBarState(SplitterBarStateType::Restored);
normalViewProperties->set_VerticalBarState(SplitterBarStateType::Maximized);
normalViewProperties->get_RestoredTop()->set_AutoAdjust(true);
normalViewProperties->get_RestoredTop()->set_DimensionSize(80.0f);
normalViewProperties->set_ShowOutlineIcons(true);
pres->Save(u"presentation_normal_view_state.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [INormalViewProperties](../inormalviewproperties/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)