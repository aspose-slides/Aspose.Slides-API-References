---
title: IBaseSlide
second_title: Aspose.Slides för C++ API-referens
description: Representerar gemensam data för alla bildtyper.
type: docs
weight: 1496
url: /sv/aspose.slides/ibaseslide/
---
## IBaseSlide klass

Representerar gemensam data för alla bildtyper.

```cpp
class IBaseSlide : public virtual Aspose::Slides::Theme::IThemeable
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | Returnerar ett effektivt tema för detta tematiserbara objekt. |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](./)\>) | Bestämmer om de två [IBaseSlide](./)-instanserna är lika. Det returnerade värdet beräknas baserat på bildens struktur och statiskt innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifieringsvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstyp-objekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil flyttalsjämförelse där två NaN-värden betraktas som lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) | Hittar första förekomsten av en form med den angivna alternativa texten. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() | Returnerar bildens bakgrund. Skrivskyddad [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) | Returnerar ActiveX-kontrollen på det angivna indexet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() | Returnerar samlingen av ActiveX-kontroller på en bild. Skrivskyddad [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | Returnerar bildens anpassade data. Skrivskyddad [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. Skrivskyddad [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | Returnerar namnet på en bild. Läs [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returnerar presentationen. Skrivskyddad [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | Returnerar formen på det angivna indexet. Skrivskyddad [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | Returnerar formerna på en bild. Skrivskyddad [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | Anger om former på huvudbilden ska visas på bilder eller inte. För själva huvudbilden returnerar denna egenskap alltid **false**. Läs **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](./)\> [get_Slide](../islidecomponent/get_slide/)() | Returnerar grundbilden. Skrivskyddad [IBaseSlide](./). |
| virtual **uint32_t** [get_SlideId](./get_slideid/)() | Returnerar ID för en bild. Skrivskyddad **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() | Returnerar TransitionEx-objektet som innehåller information om hur den angivna bilden avanceras under en bildspelsvisning. Skrivskyddad [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() | Returnerar animerings-tidslinjeobjektet. Skrivskyddad [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning med C# lock()-sats. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referensjämför ett värdetyp-objekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet sträng och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | Sätter namnet på en bild. Skriv [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | Anger om former på huvudbilden ska visas på bilder eller inte. För själva huvudbilden returnerar denna egenskap alltid **false**. Skriv **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en weak-pekare (istället för shared). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning med C# lock()-sats avlåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referensräknare. Bör inte anropas direkt; använd i stället smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [IThemeable](../../aspose.slides.theme/ithemeable/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)