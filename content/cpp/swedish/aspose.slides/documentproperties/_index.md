---
title: DocumentProperties
second_title: Aspose.Slides för C++ API-referens
description: Representerar egenskaper för en presentation.
type: docs
weight: 794
url: /sv/aspose.slides/documentproperties/
---
## DocumentProperties klass

Representerar egenskaper för en presentation.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Rensar och sätter standardvärden för alla inbyggda egenskaper. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Tar bort alla anpassade egenskaper. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klonar aktuellt objekt |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Klonar aktuellt objekt |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Kontrollerar förekomsten av en anpassad egenskap med ett specificerat namn. |
|  [DocumentProperties](./documentproperties/)() | Initierar en ny instans av klassen [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-stil jämförelse av flyttal där två NaN-värden anses lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för intern användning. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Returnerar mall för en applikation. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Returnerar programversionen. Läs-endast [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Returnerar författaren till en presentation. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Returnerar kategorin för en presentation. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Returnerar kommentarerna till en presentation. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Returnerar företags-egenskapen. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Returnerar innehållsstatus för en presentation. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Returnerar innehållstypen för en presentation. Läs [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Returnerar antalet anpassade egenskaper som faktiskt finns i en samling. Läs-endast **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Returnerar datumet då en presentation skapades. Värdena är i UTC. Läs [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Anger gruppering av dokumentdelar och antalet delar i varje grupp. Läs-endast [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Returnerar antalet dolda bilder i ett presentationsdokument. Läs-endast **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Returnerar dokumentegenskapen HyperlinkBase. Läs [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. Nästa producent som öppnar dokumentet ska uppdatera hyperlänkrelationerna med de nya hyperlänkarna som anges i denna del. Läs **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Returnerar nyckelorden för en presentation. Läs [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Returnerar datumet då en presentation senast skrevs ut. Läs [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Returnerar namnet på den sista personen som ändrade en presentation. Läs [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Läs-endast vid [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (eftersom det uppdateras internt under [IPresentation](../ipresentation/)-objektets sparprocess). Kan ändras via [DocumentProperties](./)-instans som returneras av metod [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Se exempel i [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/)-metodsammanfattning. |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Anger huruvida hyperlänkar i ett dokument är aktuella. Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade. Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade. Läs **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Returnerar manager-egenskapen. Läs [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Returnerar det totala antalet ljud- eller videoklipp som finns i dokumentet. Läs-endå **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Returnerar programmets namn. Läs [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Returnerar antalet bilder i en presentation som innehåller anteckningar. Läs-endast **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Returnerar det totala antalet stycken i ett dokument om tillämpligt. Läs-endast **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Returnerar det avsedda formatet för en presentation. Läs [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Returnerar presentationsrevisionens nummer. Läs **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Anger visningsläget för dokumentets miniatyrbild. Sätt detta element till **true** för att möjliggöra skalning av miniatyrbilden till displayen. Sätt detta element till **false** för att beskära miniatyrbilden så att endast sektioner som passar displayen visas. Läs **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Bestämmer huruvida presentationen delas mellan flera personer. Läs **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Returnerar det totala antalet bilder i ett presentationsdokument. Läs-endast **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Returnerar ämnet för en presentation. Läs [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Returnerar titeln för en presentation. Läs [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Anger titeln för varje dokumentdel. Dessa delar är inte dokumentdelar utan konceptuella representationer av dokumentssektioner. Läs-endast [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Total redigeringstid för en presentation. Läs [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Returnerar det totala antalet ord som finns i ett dokument. Läs-endast **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referenstagarnings datastruktur associerad med objektet. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Returnerar namnet på en anpassad egenskap vid angivet index. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Hämtar ett namngivet booleskt värde från de anpassade egenskaperna. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Hämtar ett namngivet heltalsvärde från de anpassade egenskaperna. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Hämtar ett namngivet DateTime-värde från de anpassade egenskaperna. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Hämtar ett namngivet strängvärde från de anpassade egenskaperna. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Hämtar ett namngivet flyttal från de anpassade egenskaperna. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Hämtar ett namngivet double-värde från de anpassade egenskaperna. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metod. Möjliggör hashning av anpassade objekt. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Hämtar en array av känslighetsetiketter från de anpassade dokumentegenskaperna (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar den faktiska typen av objektet. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Returnerar den anpassade egenskapen som är associerad med ett specificerat namn. Läs [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Sätter den anpassade egenskapen som är associerad med ett specificerat namn. Skriv [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet representerar en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metod. Möjliggör kloning av anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktör. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, utan initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referens-jämför värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet strängar. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Tar bort en anpassad egenskap som är associerad med ett specificerat namn. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar delad referenstagare med angivet värde. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Sätter mallen för en applikation. Skriv [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Sätter författaren till en presentation. Skriv [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Sätter kategorin för en presentation. Skriv [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Sätter kommentarerna till en presentation. Skriv [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Sätter företags-egenskapen. Skriv [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Sätter innehållsstatus för en presentation. Skriv [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Sätter innehållstypen för en presentation. Skriv [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Returnerar datumet då en presentation skapades. Värdena är i UTC. Skriv [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Sätter dokumentegenskapen HyperlinkBase. Skriv [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Anger att en eller flera hyperlänkar i denna del uppdaterades exklusivt i denna del av en producent. Nästa producent som öppnar dokumentet ska uppdatera hyperlänkrelationerna med de nya hyperlänkarna som anges i denna del. Skriv **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Sätter nyckelorden för en presentation. Skriv [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Returnerar datumet då en presentation senast skrevs ut. Skriv [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Sätter namnet på den sista personen som ändrade en presentation. Skriv [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Returnerar datumet då en presentation senast ändrades. Värdena är i UTC. Läs-endast vid [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (eftersom det uppdateras internt under [IPresentation](../ipresentation/)-objektets sparprocess). Kan ändras via [DocumentProperties](./)-instans som returneras av metod [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/). Se exempel i [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/)-metodsammanfattning. |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Anger huruvida hyperlänkar i ett dokument är aktuella. Sätt detta element till **true** för att indikera att hyperlänkar är uppdaterade. Sätt detta element till **false** för att indikera att hyperlänkar är föråldrade. Skriv **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Sätter manager-egenskapen. Skriv [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Sätter programmets namn. Skriv [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Sätter det avsedda formatet för en presentation. Skriv [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Sätter presentationsrevisionens nummer. Skriv **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Anger visningsläget för dokumentets miniatyrbild. Sätt detta element till **true** för att möjliggöra skalning av miniatyrbilden till displayen. Sätt detta element till **false** för att beskära miniatyrbilden så att endast sektioner som passar displayen visas. Skriv **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Bestämmer huruvida presentationen delas mellan flera personer. Skriv **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Sätter ämnet för en presentation. Skriv [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Sätter titeln för en presentation. Skriv [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Total redigeringstid för en presentation. Skriv [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Sätter en namngiven boolesk anpassad egenskap. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Sätter en namngiven heltals-anpassad egenskap. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Sätter en namngiven DateTime-anpassad egenskap. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Sätter en namngiven sträng-anpassad egenskap. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Sätter en namngiven float-anpassad egenskap. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Sätt en namngiven double-anpassad egenskap. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätt n:te mallargument till en svag pekare (istället för delad). Gör det möjligt att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för delad referenstagare. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar delad referenstagare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar delad referenstagare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metod. Möjliggör konvertering av anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar svag referenstagare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar svag referenstagare. Ska inte anropas direkt; använd smarta pekare eller ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigir alla interna datastrukturer. |

## Anmärkningar

Följande exempel visar hur man får åtkomst till inbyggda egenskaper i PowerPoint [Presentation](../presentation/).
```cpp
// Instansiera Presentation-klassen som representerar presentationen
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Följande exempel visar hur man modifierar inbyggda egenskaper i PowerPoint [Presentation](../presentation/).
```cpp
// Instansiera Presentation-klassen som representerar Presentationen
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Skapa en referens till IDocumentProperties-objektet som är associerat med Presentation
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Ställ in de inbyggda egenskaperna
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Spara din presentation till en fil
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Se även

* Klass [IDocumentProperties](../idocumentproperties/)
* Klass [IGenericCloneable](../igenericcloneable/)
* Namnrymd [Aspose::Slides](../)
* Bibliotek [Aspose.Slides](../../)