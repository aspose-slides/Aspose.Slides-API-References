---
title: PdfAccessPermissions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Bevat een reeks vlaggen die aangeven welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten.
type: docs
url: /nl/com.aspose.slides/pdfaccesspermissions/
---
**Erfelijkheid:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Bevat een reeks vlaggen die bepalen welke toegangsrechten moeten worden verleend wanneer het document wordt geopend met gebruikersrechten.
## Velden

| Veld | Beschrijving |
| --- | --- |
| [None](#None) | Specificeert dat een gebruiker geen toegangsrechten heeft. |
| [PrintDocument](#PrintDocument) | Specificeert of een gebruiker het document mag afdrukken (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ook is ingesteld). |
| [ModifyContent](#ModifyContent) | Specificeert of een gebruiker de inhoud van het document mag wijzigen via bewerkingen anders dan die gecontroleerd worden door bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Specificeert of een gebruiker tekst en afbeeldingen uit het document mag kopiëren of op andere wijze extraheren via bewerkingen anders dan die gecontroleerd worden door bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Specificeert of een gebruiker tekstannotaties mag toevoegen of wijzigen, interactieve formuliervelden mag invullen, en, indien bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ook is ingesteld, interactieve formuliervelden (inclusief handtekeningvelden) mag aanmaken of wijzigen. |
| [FillExistingFields](#FillExistingFields) | Specificeert of een gebruiker bestaande interactieve formuliervelden (inclusief handtekeningvelden) mag invullen, zelfs als bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) niet is ingesteld. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Specificeert of een gebruiker tekst en afbeeldingen mag extraheren ter ondersteuning van toegankelijkheid voor gebruikers met een handicap of voor andere doeleinden. |
| [AssembleDocument](#AssembleDocument) | Specificeert of een gebruiker het document mag samenstellen (pagina's invoegen, roteren of verwijderen en bladwijzers of miniatuurafbeeldingen aanmaken), zelfs als bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) niet is ingesteld. |
| [HighQualityPrint](#HighQualityPrint) | Specificeert of een gebruiker het document mag afdrukken naar een representatie waaruit een getrouwe digitale kopie van de PDF-inhoud kan worden gegenereerd. |
### None {#None}
```
public static final int None
```

Specificeert dat een gebruiker geen toegangsrechten heeft.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Specificeert of een gebruiker het document mag afdrukken (mogelijk niet op het hoogste kwaliteitsniveau, afhankelijk van of bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) ook is ingesteld).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Specificeert of een gebruiker de inhoud van het document mag wijzigen via bewerkingen anders dan die gecontroleerd worden door bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Specificeert of een gebruiker tekst en afbeeldingen uit het document mag kopiëren of op andere wijze extraheren via bewerkingen anders dan die gecontroleerd worden door bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Specificeert of een gebruiker tekstannotaties mag toevoegen of wijzigen, interactieve formuliervelden mag invullen, en, indien bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) ook is ingesteld, interactieve formuliervelden (inclusief handtekeningvelden) mag aanmaken of wijzigen.

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Specificeert of een gebruiker bestaande interactieve formuliervelden (inclusief handtekeningvelden) mag invullen, zelfs als bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) niet is ingesteld.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Specificeert of een gebruiker tekst en afbeeldingen mag extraheren ter ondersteuning van toegankelijkheid voor gebruikers met een handicap of voor andere doeleinden.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Specificeert of een gebruiker het document mag samenstellen (pagina's invoegen, roteren of verwijderen en bladwijzers of miniatuurafbeeldingen aanmaken), zelfs als bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) niet is ingesteld.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Specificeert of een gebruiker het document mag afdrukken naar een representatie waaruit een getrouwe digitale kopie van de PDF-inhoud kan worden gegenereerd. Wanneer dit bit niet is ingesteld (en bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) wel is ingesteld), is afdrukken beperkt tot een laag-niveau weergave van het uiterlijk, mogelijk van verminderde kwaliteit.