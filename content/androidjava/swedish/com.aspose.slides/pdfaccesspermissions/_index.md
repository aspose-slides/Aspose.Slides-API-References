---
title: PdfAccessPermissions
second_title: Aspose.Slides för Android via Java API-referens
description: Innehåller en uppsättning flaggor som specificerar vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst.
type: docs
url: /sv/com.aspose.slides/pdfaccesspermissions/
---
**Arv:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Innehåller en uppsättning flaggor som anger vilka åtkomstbehörigheter som ska beviljas när dokumentet öppnas med användaråtkomst.
## Fält

| Field | Description |
| --- | --- |
| [None](#None) | Anger att en användare inte har åtkomstbehörigheter. |
| [PrintDocument](#PrintDocument) | Anger om en användare får skriva ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på om bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) också är satt). |
| [ModifyContent](#ModifyContent) | Anger om en användare får ändra innehållet i dokumentet genom operationer som inte styrs av bitarna [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields) och [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Anger om en användare får kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Anger om en användare får lägga till eller ändra textanteckningar, fylla i interaktiva formulärfält och, om bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) också är satt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält). |
| [FillExistingFields](#FillExistingFields) | Anger om en användare får fylla i befintliga interaktiva formulärfält (inklusive signaturfält), även om bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) är rensad. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Anger om en användare får extrahera text och grafik för att stödja tillgänglighet för användare med funktionshinder eller för andra ändamål. |
| [AssembleDocument](#AssembleDocument) | Anger om en användare får sammanfoga dokumentet (infoga, rotera eller ta bort sidor samt skapa bokmärken eller miniatyrbilder), även om bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) är rensad. |
| [HighQualityPrint](#HighQualityPrint) | Anger om en användare får skriva ut dokumentet till en representation från vilken en exakt digital kopia av PDF-innehållet kan genereras. |
### None {#None}
```
public static final int None
```

Anger att en användare inte har åtkomstbehörigheter.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Anger om en användare får skriva ut dokumentet (möjligen inte på högsta kvalitetsnivå, beroende på om bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) också är satt).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Anger om en användare får ändra innehållet i dokumentet genom operationer som inte styrs av bitarna [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields) och [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Anger om en användare får kopiera eller på annat sätt extrahera text och grafik från dokumentet genom operationer som inte styrs av bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Anger om en användare får lägga till eller ändra textanteckningar, fylla i interaktiva formulärfält och, om bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) också är satt, skapa eller ändra interaktiva formulärfält (inklusive signaturfält).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Anger om en användare får fylla i befintliga interaktiva formulärfält (inklusive signaturfält), även om bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) är rensad.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Anger om en användare får extrahera text och grafik för att stödja tillgänglighet för användare med funktionshinder eller för andra ändamål.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Anger om en användare får sammanfoga dokumentet (infoga, rotera eller ta bort sidor samt skapa bokmärken eller miniatyrbilder), även om bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) är rensad.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Anger om en användare får skriva ut dokumentet till en representation från vilken en exakt digital kopia av PDF-innehållet kan genereras. När den här biten är rensad (och bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) är satt) begränsas utskriften till en låg nivå-representation av utseendet, möjligen med försämrad kvalitet.