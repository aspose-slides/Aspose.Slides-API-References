---
title: LoadOptions
second_title: Aspose.Sildes för .NET API-referens
description: Tillåter att ange ytterligare alternativ såsom format eller standardteckensnitt när en presentation läses in.
type: docs
weight: 7840
url: /sv/aspose.slides/loadoptions/
---
# LoadOptions klass

Tillåter att ange ytterligare alternativ (t.ex. format eller standardtypsnitt) vid inläsning av en presentation.

```csharp
public class LoadOptions : ILoadOptions
```

## Konstruktörer

| Name | Description |
| --- | --- |
| [LoadOptions](loadoptions#constructor)() | Skapar nya standardinläsningsalternativ. |
| [LoadOptions](loadoptions#constructor_1)(LoadFormat) | Skapar nya inläsningsalternativ. |

## Egenskaper

| Name | Description |
| --- | --- |
| [BlobManagementOptions](../../aspose.slides/loadoptions/blobmanagementoptions) { get; set; } | Representerar de alternativ som kan användas för att hantera beteendet för Binary Large Objects (BLOBs), såsom användning av temporära filer eller maximalt antal BLOB-bytes i minnet. Dessa alternativ är avsedda att konfigurera det bästa förhållandet mellan prestanda och minnesanvändning för en särskild miljö eller krav. En Binary Large Object (BLOB) är binär data lagrad som en enhet – t.ex. kan en BLOB vara ett ljud, en video eller själva presentationen. |
| [DefaultAsianFont](../../aspose.slides/loadoptions/defaultasianfont) { get; set; } | Returnerar eller anger ett asiatiskt teckensnitt som används om källteckensnittet inte hittas. Read/write String. |
| [DefaultRegularFont](../../aspose.slides/loadoptions/defaultregularfont) { get; set; } | Returnerar eller anger ett vanligt teckensnitt som används om källteckensnittet inte hittas. Read/write String. |
| [DefaultSymbolFont](../../aspose.slides/loadoptions/defaultsymbolfont) { get; set; } | Returnerar eller anger Symbol-teckensnitt som används om källteckensnittet inte hittas. Read/write String. |
| [DefaultTextLanguage](../../aspose.slides/loadoptions/defaulttextlanguage) { get; set; } | Returnerar eller anger standardspråket för presentationstext. Read/write String. |
| [DeleteEmbeddedBinaryObjects](../../aspose.slides/loadoptions/deleteembeddedbinaryobjects) { get; set; } | Bestämmer om Aspose.Slides ska ta bort alla inbäddade binära objekt vid inläsning av presentationen. |
| [DocumentLevelFontSources](../../aspose.slides/loadoptions/documentlevelfontsources) { get; set; } | Anger källor för externa teckensnitt som ska användas av presentationen. Dessa teckensnitt är tillgängliga för presentationen under hela dess livstid och delas inte med andra presentationer |
| [InterruptionToken](../../aspose.slides/loadoptions/interruptiontoken) { get; set; } | Tokenet för att övervaka avbrottsförfrågningar.  Detta token hanterar hela [`IPresentation`](../ipresentation)-instansens livstid. Alla långvariga operationer, såsom inläsning eller sparande av en presentation, avbryts genom att anropa [`Interrupt`](../interruptiontokensource/interrupt)-metoden i [`InterruptionTokenSource`](../interruptiontokensource). |
| [LoadFormat](../../aspose.slides/loadoptions/loadformat) { get; set; } | Returnerar eller anger formatet för en presentation som ska läsas in. Read/write [`LoadFormat`](../loadformat). |
| [OnlyLoadDocumentProperties](../../aspose.slides/loadoptions/onlyloaddocumentproperties) { get; set; } | Denna egenskap är relevant om presentationsfilen är lösenordsskyddad. Värdet true innebär att endast dokumentegenskaper ska läsas in från en krypterad presentationsfil och lösenordet ska ignoreras. Värdet false innebär att hela den krypterade presentationen ska läsas in med korrekt lösenord. Om presentationen inte är krypterad ignoreras egenskapens värde alltid. Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapens värde är true, kan inte dokumentegenskaperna läsas in och ett undantag kastas. Read/write Boolean. |
| [Password](../../aspose.slides/loadoptions/password) { get; set; } | Hämtar eller anger lösenordet. Read/write String. |
| [ResourceLoadingCallback](../../aspose.slides/loadoptions/resourceloadingcallback) { get; set; } | Returnerar eller anger återuppringningsgränssnitt som hanterar inläsning av externa resurser. Read/write [`IResourceLoadingCallback`](../iresourceloadingcallback). |
| [SpreadsheetOptions](../../aspose.slides/loadoptions/spreadsheetoptions) { get; set; } | Hämtar alternativ för kalkylblad. Till exempel påverkar dessa alternativ beräkning av formler för diagram. |
| [WarningCallback](../../aspose.slides/loadoptions/warningcallback) { get; set; } | Returnerar eller anger ett objekt som tar emot varningar och bestämmer om inläsningsprocessen ska fortsätta eller avbrytas. Read/write [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Se även

* gränssnitt [ILoadOptions](../iloadoptions)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->