---
title: ILoadOptions
second_title: Aspose.Slides för C++ API-referens
description: Tillåter att ange ytterligare alternativ (såsom format eller standardteckensnitt) när en presentation laddas.
type: docs
weight: 2796
url: /sv/aspose.slides/iloadoptions/
---
## ILoadOptions klass

Tillåter att ange ytterligare alternativ (såsom format eller standardteckensnitt) när en presentation laddas.

```cpp
class ILoadOptions : public virtual System::Object
```

## Metoder

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Jämför objekt med C# [Object.Equals](../../system/object/equals/)-semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför referenstypobjekt i C#-stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Jämför värdetypobjekt i C#-stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulerar C#-liknande flyttalsjämförelse där två NaN-värden betraktas som lika även om IEC 60559:1989 anger att NaN inte är lika med något värde, inklusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Endast för internt bruk. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() | Representerar alternativ som kan användas för att hantera beteendet för Binary Large Objects (BLOBs), såsom användning av temporära filer eller maximalt antal BLOB-byte i minnet. Dessa alternativ är avsedda att ställa in det bästa förhållandet mellan prestanda och minnesförbrukning för en viss miljö eller krav. |
| virtual [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() | Returnerar ett asiatiskt teckensnitt som används om källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() | Returnerar vanligt teckensnitt som används om källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() | Returnerar Symbol-teckensnitt som används om källteckensnittet inte hittas. Läser [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() | Returnerar standardspråket för presentationstext. Läser [System::String](../../system/string/). |
| virtual **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() | Avgör om [Aspose.Slides](../) kommer att ta bort alla inbäddade binära objekt under presentationens inläsning. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() | Anger källor för externa teckensnitt som ska användas av presentationen. Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() | Token för att övervaka avbrotts-förfrågningar. |
| virtual [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() | Returnerar formatet för en presentation som ska laddas. Läser [Slides::LoadFormat](../loadformat/). |
| virtual **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() | Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska läsas från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen måste läsas med rätt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapens värde är true kan dokumentegenskaperna inte läsas och ett undantag kommer att kastas. Läser **bool**. |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | Hämtar lösenordet. Läser [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() | Returnerar återuppringningsgränssnitt som hanterar inläsning av externa resurser. Läser [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() | Representerar alternativ som kan användas för att ange ytterligare beteende för kalkylblad. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() | Returnerar ett objekt som tar emot varningar och avgör om inläsningsprocessen ska fortsätta eller avbrytas. Läser [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Hämtar referensräknarens datastruktur som är associerad med objektet. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog till C# [Object.GetHashCode()](../../system/object/gethashcode/)-metoden. Gör det möjligt att skapa hash för anpassade objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Hämtar objektets faktiska typ. Analog till C# [System.Object.GetType()](../../system/object/gettype/)-anrop. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Kontrollerar om objektet är en instans av den typ som beskrivs av targetType. Analog till C#-operatorn 'is'. |
| void [Lock](../../system/object/lock/)() | Implementerar C# lock()-satsens låsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog till C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-metoden. Gör det möjligt att klona anpassade typer. |
|  [Object](../../system/object/object/)() | Skapar objekt. Initierar alla interna datastrukturer. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopieringskonstruktor. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Tilldelningsoperator. Kopierar egentligen ingenting, den initierar bara ett nytt objekt och möjliggör kopiekonstruktion av underklasser. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Jämför objekt efter referens. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Jämför referensmässigt ett värdetypobjekt med nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet string och nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisering av [Object::ReferenceEquals](../../system/object/referenceequals/) för fallet med strängar. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Minskar det delade referensräknaren med angivet värde. |
| virtual void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) | Representerar alternativ som kan användas för att hantera beteendet för Binary Large Objects (BLOBs), såsom användning av temporära filer eller maximalt antal BLOB-byte i minnet. Dessa alternativ är avsedda att ställa in det bästa förhållandet mellan prestanda och minnesförbrukning för en viss miljö eller krav. |
| virtual void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) | Ställer in asiatiskt teckensnitt som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| virtual void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) | Ställer in vanligt teckensnitt som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| virtual void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) | Ställer in Symbol-teckensnitt som används om källteckensnittet inte hittas. Skriver [System::String](../../system/string/). |
| virtual void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) | Ställer in standardspråket för presentationstext. Skriver [System::String](../../system/string/). |
| virtual void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) | Avgör om [Aspose.Slides](../) kommer att ta bort alla inbäddade binära objekt under presentationens inläsning. |
| virtual void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) | Anger källor för externa teckensnitt som ska användas av presentationen. Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer |
| virtual void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) | Token för att övervaka avbrotts-förfrågningar. |
| virtual void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) | Ställer in formatet för en presentation som ska laddas. Skriver [Slides::LoadFormat](../loadformat/). |
| virtual void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) | Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true betyder att endast dokumentegenskaper ska läsas från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false betyder att hela den krypterade presentationen måste läsas med rätt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapens värde är true kan dokumentegenskaperna inte läsas och ett undantag kastas. Skriver **bool**. |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | Ställer in lösenordet. Skriver [System::String](../../system/string/). |
| virtual void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) | Ställer in återuppringningsgränssnitt som hanterar inläsning av externa resurser. Skriver [IResourceLoadingCallback](../iresourceloadingcallback/). |
| virtual void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) | Representerar alternativ som kan användas för att ange ytterligare beteende för kalkylblad. |
| virtual void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Ställer in ett objekt som tar emot varningar och avgör om inläsningsprocessen ska fortsätta eller avbrytas. Skriver [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Sätter n'te templatattribut till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
| int [SharedCount](../../system/object/sharedcount/)() const | Hämtar aktuellt värde för det delade referensräknaren. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ökar det delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Minskar och returnerar det delade referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog till C# [Object.ToString()](../../system/object/tostring/)-metoden. Gör det möjligt att konvertera anpassade objekt till sträng. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementerar C# typeof([System.Object](../../system/object/))-konstruktionen. |
| void [Unlock](../../system/object/unlock/)() | Implementerar C# lock()-satsens upplåsning. Anropa direkt eller använd [LockContext](../../system/lockcontext/)-vaktobjekt. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Ökar den svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector istället. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Minskar den svaga referensräknaren. Bör inte anropas direkt; använd smarta pekare eller ThisProtector ändå. |
| virtual  [~Object](../../system/object/~object/)() | Förstör objektet. Frigör alla interna datastrukturer. |

## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)