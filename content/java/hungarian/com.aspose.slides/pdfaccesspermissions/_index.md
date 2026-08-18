---
title: PdfAccessPermissions
second_title: Aspose.Slides Java API Referenciája
description: Tartalmaz egy sor jelzőt, amely meghatározza, hogy milyen hozzáférési jogosultságokat kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg.
type: docs
url: /hu/com.aspose.slides/pdfaccesspermissions/
---
**Öröklődés:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Tartalmaz egy sor jelzőt, amely meghatározza, hogy milyen hozzáférési jogosultságokat kell megadni, amikor a dokumentum felhasználói hozzáféréssel nyílik meg.
## Mezők

| Mező | Leírás |
| --- | --- |
| [None](#None) | Megadja, hogy a felhasználónak nincs hozzáférési jogosultsága. |
| [PrintDocument](#PrintDocument) | Megadja, hogy a felhasználó nyomtathatja-e a dokumentumot (esetleg nem a legmagasabb minőségi szinten, attól függően, hogy a(z) [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) bit is be van-e állítva). |
| [ModifyContent](#ModifyContent) | Megadja, hogy a felhasználó módosíthatja-e a dokumentum tartalmát olyan műveletekkel, amelyek nem a(z) [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) bitek által szabályozottak. |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Megadja, hogy a felhasználó másolhat-e vagy egyéb módon kinyerheti-e a szöveget és a grafikákat a dokumentumból olyan műveletekkel, amelyek nem a(z) [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) bit által szabályozottak. |
| [AddOrModifyFields](#AddOrModifyFields) | Megadja, hogy a felhasználó hozzáadhat-e vagy módosíthat-e szöveges jegyzeteket, kitöltheti-e az interaktív űrlapmezőket, és ha a(z) [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bit is be van állítva, létrehozhat-e vagy módosíthat-e interaktív űrlapmezőket (beleértve az aláírási mezőket is). |
| [FillExistingFields](#FillExistingFields) | Megadja, hogy a felhasználó kitöltheti-e a már meglévő interaktív űrlapmezőket (beleértve az aláírási mezőket is), akkor is, ha a(z) [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) bit nincs beállítva. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Megadja, hogy a felhasználó kinyerheti-e a szöveget és a grafikákat a fogyatékkal élő felhasználók akadálymentesítésének támogatására vagy egyéb célokra. |
| [AssembleDocument](#AssembleDocument) | Megadja, hogy a felhasználó összeállíthatja-e a dokumentumot (oldalak beszúrása, forgatása vagy törlése, valamint könyvjelzők vagy miniatűr képek létrehozása), akkor is, ha a(z) [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bit nincs beállítva. |
| [HighQualityPrint](#HighQualityPrint) | Megadja, hogy a felhasználó nyomtathat-e a dokumentumot egy olyan ábrázolásra, amelyből a PDF tartalom hűséges digitális másolata előállítható. |
### None {#None}
```
public static final int None
```


Megadja, hogy a felhasználónak nincs hozzáférési jogosultsága.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```


Megadja, hogy a felhasználó nyomtathatja-e a dokumentumot (esetleg nem a legmagasabb minőségi szinten, attól függően, hogy a(z) [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) bit is be van-e állítva).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```


Megadja, hogy a felhasználó módosíthatja-e a dokumentum tartalmát olyan műveletekkel, amelyek nem a(z) [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument) bitek által szabályozottak.

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```


Megadja, hogy a felhasználó másolhat-e vagy egyéb módon kinyerheti-e a szöveget és a grafikákat a dokumentumból olyan műveletekkel, amelyek nem a(z) [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics) bit által szabályozottak.

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```


Megadja, hogy a felhasználó hozzáadhat-e vagy módosíthat-e szöveges jegyzeteket, kitöltheti-e az interaktív űrlapmezőket, és ha a(z) [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bit is be van állítva, létrehozhat-e vagy módosíthat-e interaktív űrlapmezőket (beleértve az aláírási mezőket is).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```


Megadja, hogy a felhasználó kitöltheti-e a már meglévő interaktív űrlapmezőket (beleértve az aláírási mezőket is), akkor is, ha a(z) [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) bit nincs beállítva.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```


Megadja, hogy a felhasználó kinyerheti-e a szöveget és a grafikákat a fogyatékkal élő felhasználók akadálymentesítésének támogatására vagy egyéb célokra.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```


Megadja, hogy a felhasználó összeállíthatja-e a dokumentumot (oldalak beszúrása, forgatása vagy törlése, valamint könyvjelzők vagy miniatűr képek létrehozása), akkor is, ha a(z) [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) bit nincs beállítva.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```


Megadja, hogy a felhasználó nyomtathat-e a dokumentumot egy olyan ábrázolásra, amelyből a PDF tartalom hűséges digitális másolata előállítható. Ha ez a bit nincs beállítva (és a(z) [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) bit be van állítva), a nyomtatás alacsony szintű megjelenítési formára korlátozódik, esetleg lerontott minőségben.