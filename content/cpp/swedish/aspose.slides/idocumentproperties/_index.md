---
title: IDocumentProperties
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskaper för en presentation.
type: docs
weight: 1977
url: /sv/aspose.slides/idocumentproperties/
---
## IDocumentProperties klass

Representerar egenskaper för en presentation.

```cpp
class IDocumentProperties : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual void [ClearBuiltInProperties](./clearbuiltinproperties/)() | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| virtual void [ClearCustomProperties](./clearcustomproperties/)() | Tar bort alla anpassade egenskaper. |
| virtual **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) | Kontrollerar förekomsten av en anpassad egenskap med ett specificerat namn. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av referenstyp i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför objekt av värdetyp i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar flyttalsjämförelse i C#-stil där två NaN-värden anses lika även om enligt IEC 60559:1989 är NaN inte lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för interna ändamål. |
| virtual [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() | Returnerar mall för en applikation. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() | Returnerar programversionen. Skrivskyddad [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Author](./get_author/)() | Returnerar författaren till en presentation. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Category](./get_category/)() | Returnerar kategorin för en presentation. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Comments](./get_comments/)() | Returnerar kommentarer för en presentation. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Company](./get_company/)() | Returnerar företagsegenskapen. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() | Returnerar innehållsstatus för en presentation. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() | Returnerar innehållstypen för en presentation. Läs [System::String](../../system/string/). |
| virtual **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. Skrivskyddad **int32_t**. |
| virtual [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() | Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs [System::DateTime](../../system/datetime/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() | Anger gruppering av dokumentdelar och antalet delar i varje grupp. Skrivskyddad [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| virtual **int32_t** [get_HiddenSlides](./get_hiddenslides/)() | Anger antalet dolda bilder i ett presentationsdokument. Skrivskyddad **int32_t**. |
| virtual [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() | Returnerar dokumentegenskapen HyperlinkBase. Läs [System::String](../../system/string/). |
| virtual **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() | Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänkrelationerna med de nya hyperlänkarna som specificerats i denna del. Läs **bool**. |
| virtual [System::String](../../system/string/) [get_Keywords](./get_keywords/)() | Returnerar nyckelorden för en presentation. Läs [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() | Returnerar datumet då en presentation senast skrevs ut. Läs [System::DateTime](../../system/datetime/). |
| virtual [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() | Returnerar namnet på den senaste personen som modifierade en presentation. Läs [System::String](../../system/string/). |
| virtual [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() | Returnerar datumet då en presentation senast modifierades. Värdena är i UTC. Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den kommer att uppdateras internt under [IPresentation](../ipresentation/) objektets sparprocess). Kan ändras via [DocumentProperties](../documentproperties/)-instansen som returneras av metoden [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Se exempel i [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) metodsammanfattning. |
| virtual **bool** [get_LinksUpToDate](./get_linksuptodate/)() | Anger om hyperlänkar i ett dokument är aktuella. Ställ in detta element till **true** för att indikera att hyperlänkar är uppdaterade. Ställ in detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs **bool**. |
| virtual [System::String](../../system/string/) [get_Manager](./get_manager/)() | Returnerar manager-egenskapen. Läs [System::String](../../system/string/). |
| virtual **int32_t** [get_MultimediaClips](./get_multimediaclips/)() | Anger det totala antalet ljud- eller videoklipp som finns i dokumentet. Skrivskyddad **int32_t**. |
| virtual [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() | Returnerar applikationens namn. Läs [System::String](../../system/string/). |
| virtual **int32_t** [get_Notes](./get_notes/)() | Anger antalet bilder i en presentation som innehåller anteckningar. Skrivskyddad **int32_t**. |
| virtual **int32_t** [get_Paragraphs](./get_paragraphs/)() | Anger det totala antalet stycken som finns i ett dokument, om tillämpligt. Skrivskyddad **int32_t**. |
| virtual [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() | Returnerar det avsedda formatet för en presentation. Läs [System::String](../../system/string/). |
| virtual **int32_t** [get_RevisionNumber](./get_revisionnumber/)() | Returnerar presentations revisionsnummer. Läs **int32_t**. |
| virtual **bool** [get_ScaleCrop](./get_scalecrop/)() | Anger visningsläget för dokumentets miniatyrbild. Ställ in detta element till **true** för att möjliggöra skalning av miniatyrbilden till skärmen. Ställ in detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar skärmen visas. Läs **bool**. |
| virtual **bool** [get_SharedDoc](./get_shareddoc/)() | Bestämmer om presentationen delas mellan flera personer. Läs **bool**. |
| virtual **int32_t** [get_Slides](./get_slides/)() | Anger det totala antalet bilder i ett presentationsdokument. Skrivskyddad **int32_t**. |
| virtual [System::String](../../system/string/) [get_Subject](./get_subject/)() | Returnerar ämnet för en presentation. Läs [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Returnerar titeln för en presentation. Läs [System::String](../../system/string/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() | Anger titeln för varje dokumentdel. Dessa delar är inte dokumentdelar utan konceptuella representationer av dokumentsektioner. Skrivskyddad [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| virtual [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() | Total redigeringstid för en presentation. Läs [System::TimeSpan](../../system/timespan/). |
| virtual **int32_t** [get_Words](./get_words/)() | Anger det totala antalet ord som finns i ett dokument. Skrivskyddad **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) | Returnerar ett anpassat egenskapsnamn på angivet index. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) | Hämtar ett namngivet boolean-värde från de anpassade egenskaperna. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) | Hämtar ett namngivet heltalsvärde från de anpassade egenskaperna. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) | Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) | Hämtar ett namngivet strängvärde från de anpassade egenskaperna. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) | Hämtar ett namngivet float-värde från de anpassade egenskaperna. |
| virtual void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) | Hämtar ett namngivet double-värde från de anpassade egenskaperna. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Möjliggör hashning av anpassade objekt. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() | Hämtar en array av känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anropet. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) | Returnerar den anpassade egenskapen som är associerad med ett specificerat namn. Läs [System::Object](../../system/object/). |
| virtual void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Sätter den anpassade egenskapen som är associerad med ett specificerat namn. Skriv [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av typen som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar låsning enligt C# lock()-satser. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopieringskonstruktion av subklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt via referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strings. |
| virtual **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) | Tar bort en anpassad egenskap som är associerad med ett specificerat namn. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referensräknare med angivet värde. |
| virtual void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) | Sätter mall för en applikation. Skriv [System::String](../../system/string/). |
| virtual void [set_Author](./set_author/)([System::String](../../system/string/)) | Sätter författaren till en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_Category](./set_category/)([System::String](../../system/string/)) | Sätter kategorin för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_Comments](./set_comments/)([System::String](../../system/string/)) | Sätter kommentarer för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_Company](./set_company/)([System::String](../../system/string/)) | Sätter företagsegenskapen. Skriv [System::String](../../system/string/). |
| virtual void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) | Sätter innehållsstatus för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) | Sätter innehållstyp för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) | Returnerar datumet då en presentation skapades. Värdena är i UTC. Skriv [System::DateTime](../../system/datetime/). |
| virtual void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) | Sätter dokumentegenskapen HyperlinkBase. Skriv [System::String](../../system/string/). |
| virtual void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) | Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. Nästa producent som öppnar detta dokument ska uppdatera hyperlänkrelationerna med de nya hyperlänkarna som specificerats i denna del. Skriv **bool**. |
| virtual void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) | Sätter nyckelorden för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) | Returnerar datumet då en presentation senast skrevs ut. Skriv [System::DateTime](../../system/datetime/). |
| virtual void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) | Sätter namnet på den senaste personen som modifierade en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) | Returnerar datumet då en presentation senast modifierades. Värdena är i UTC. Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den kommer att uppdateras internt under [IPresentation](../ipresentation/) objektets sparprocess). Kan ändras via [DocumentProperties](../documentproperties/)-instansen som returneras av metoden [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Se exempel i [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/) metodsammanfattning. |
| virtual void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) | Anger om hyperlänkar i ett dokument är aktuella. Ställ in detta element till **true** för att indikera att hyperlänkar är uppdaterade. Ställ in detta element till **false** för att indikera att hyperlänkar är föråldrade. Skriv **bool**. |
| virtual void [set_Manager](./set_manager/)([System::String](../../system/string/)) | Sätter manager-egenskapen. Skriv [System::String](../../system/string/). |
| virtual void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) | Sätter applikationens namn. Skriv [System::String](../../system/string/). |
| virtual void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) | Sätter det avsedda formatet för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) | Sätter presentations revisionsnummer. Skriv **int32_t**. |
| virtual void [set_ScaleCrop](./set_scalecrop/)(**bool**) | Anger visningsläget för dokumentets miniatyrbild. Ställ in detta element till **true** för att möjliggöra skalning av miniatyrbilden till skärmen. Ställ in detta element till **false** för att möjliggöra beskärning av miniatyrbilden så att endast sektioner som passar skärmen visas. Skriv **bool**. |
| virtual void [set_SharedDoc](./set_shareddoc/)(**bool**) | Bestämmer om presentationen delas mellan flera personer. Skriv **bool**. |
| virtual void [set_Subject](./set_subject/)([System::String](../../system/string/)) | Sätter ämnet för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Sätter titeln för en presentation. Skriv [System::String](../../system/string/). |
| virtual void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) | Total redigeringstid för en presentation. Skriv [System::TimeSpan](../../system/timespan/). |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) | Sätter en namngiven boolean-egenskap. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) | Sätter en namngiven heltals-egenskap. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) | Sätter en namngiven DateTime-egenskap. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) | Sätter en namngiven sträng-egenskap. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) | Sätter en namngiven float-egenskap. |
| virtual void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) | Sätter en namngiven double-egenskap. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Ställer in n'te mallargument till en weak-pekare (istället för shared). Möjliggör byte av pekare i behållare till weak-läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde på delad referensräknare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementerar låsning enligt C# lock()-satser för upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktsobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar weak-referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar weak-referensräknare. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objekt. Frigör alla interna datastrukturer. |

## Se även

* Klass [Object](../../system/object/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)