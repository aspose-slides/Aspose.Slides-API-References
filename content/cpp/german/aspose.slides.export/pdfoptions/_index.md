---
title: PdfOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.
type: docs
weight: 573
url: /de/aspose.slides.export/pdfoptions/
---
## PdfOptions Klasse

Stellt Optionen bereit, die steuern, wie eine Präsentation im Pdf-Format gespeichert wird.

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-artige Gleitkomma-Vergleiche, bei denen zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-artige Gleitkomma-Vergleiche, bei denen zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. Siehe [PdfAccessPermissions](../pdfaccesspermissions/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | Gibt ein Array von benutzerdefinierten Schriftfamiliennamen zurück, die [Aspose.Slides](../../aspose.slides/) als gängig betrachten sollte. Lesen [System::String](../../system/string/)[]. |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | Wendet die angegebene transparente Farbe auf ein Bild an, wenn **true**. |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn auf **bool**.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | Gewünschtes Konformitätslevel für das erzeugte PDF-Dokument. Lesen [PdfCompliance](../pdfcompliance/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Gibt die Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Lesen [System::String](../../system/string/). |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Lesen **bool**. |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Lesen **bool**. |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | Bestimmt, ob [Aspose.Slides](../../aspose.slides/) gängige Schriftarten für ASCII-Text (Codebereich 33..127) einbetten wird. [Fonts](../../aspose.slides/fonts/) für Zeichenkodierungen größer als 127 werden immer eingebettet. Die Liste gängiger Schriftarten umfasst die 14 Basis-Schriftarten von PDF sowie zusätzlich vom Benutzer angegebene Schriftarten. Lesen **bool**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gibt den visuellen Stil des Farbverlaufs zurück. Lesen [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | Ermittelt die transparente Bildfarbe. |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Lesen **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Bietet Optionen, die das Aussehen von [Ink](../../aspose.slides.ink/)-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | Gibt einen Wert zurück, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen **uint8_t**. |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | Setzt das Benutzerpasswort zum Schutz des PDF-Dokuments. Lesen [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stellt ein Rückruf-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine fette Formatierung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriftarten verbessern. Lesen **bool**. |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Lesen **bool**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Lesen **bool**. Der Standardwert ist **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Ermittelt den Modus, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../islideslayoutoptions/). |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | Gibt einen Wert zurück, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | Gibt den Kompressionstyp an, der für alle textlichen Inhalte im Dokument verwendet werden soll. Lesen [PdfTextCompression](../pdftextcompression/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Gibt ein Objekt zurück oder setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
|  [PdfOptions](./pdfoptions/)() | Standardkonstruktor. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht einen Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | Enthält eine Menge von Flags, die angeben, welche Zugriffsberechtigungen beim Öffnen des Dokuments mit Benutzerzugriff gewährt werden sollen. Siehe [PdfAccessPermissions](../pdfaccesspermissions/). |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Setzt ein Array von benutzerdefinierten Schriftfamiliennamen, die [Aspose.Slides](../../aspose.slides/) als gängig betrachten sollte. Schreiben [System::String](../../system/string/)[]. |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | Wendet die angegebene transparente Farbe auf ein Bild an, wenn **true**. |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | Gibt an, ob die effektivste Kompression (statt der Standardkompression) für jedes Bild automatisch ausgewählt werden muss. Wenn auf **bool**.true gesetzt, wird für jedes Bild in der Präsentation der am besten geeignete Kompressionsalgorithmus gewählt, was zu einer kleineren Größe des resultierenden PDF-Dokuments führt. |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | Gewünschtes Konformitätslevel für das erzeugte PDF-Dokument. Schreiben [PdfCompliance](../pdfcompliance/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Setzt die zu verwendende Schriftart, falls die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | True, um einen schwarzen Rahmen um jede Folie zu zeichnen. Schreiben **bool**. |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | Bestimmt, ob alle Zeichen der Schriftart eingebettet werden sollen oder nur ein Teil verwendet wird. Schreiben **bool**. |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | Bestimmt, ob [Aspose.Slides](../../aspose.slides/) gängige Schriftarten für ASCII-Text (Codebereich 33..127) einbetten wird. [Fonts](../../aspose.slides/fonts/) für Zeichenkodierungen größer als 127 werden immer eingebettet. Die Liste gängiger Schriftarten umfasst die 14 Basis-Schriftarten von PDF sowie zusätzlich vom Benutzer angegebene Schriftarten. Schreiben **bool**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Setzt den visuellen Stil des Farbverlaufs. Schreiben [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | Setzt die transparente Farbe des Bildes. |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | True, um alle OLE-Daten aus der Präsentation in eingebettete Dateien im resultierenden PDF zu konvertieren. Schreiben **bool**. |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | Setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Schreiben **uint8_t**. |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | Setzt das Benutzerpasswort zum Schutz des PDF-Dokuments. Schreiben [System::String](../../system/string/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stellt ein Rückruf-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | Gibt an, ob Text als Bitmap gerastert und in PDF gespeichert werden soll, wenn die Schriftart keine fette Formatierung unterstützt. Dieser Ansatz kann die Textqualität im resultierenden PDF für bestimmte Schriftarten verbessern. Schreiben **bool**. |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | True, um alle in einer Präsentation verwendeten Metadateien in PNG-Bilder zu konvertieren. Schreiben **bool**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Schreiben **bool**. Der Standardwert ist **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../islideslayoutoptions/). |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | Setzt einen Wert, der die Auflösung der Bilder im PDF-Dokument bestimmt. |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | Gibt den Kompressionstyp an, der für alle textlichen Inhalte im Dokument verwendet werden soll. Schreiben [PdfTextCompression](../pdftextcompression/). |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Gibt ein Objekt zurück oder setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreiben [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Hinweise

Das folgende Beispiel zeigt, wie PowerPoint mit benutzerdefinierten Optionen in PDF konvertiert wird. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instanziert die PdfOptions-Klasse
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Setzt die JPEG-Qualität
pdfOptions->set_JpegQuality(90);
// Setzt das Verhalten für Metadateien
pdfOptions->set_SaveMetafilesAsPng(true);
// Setzt das Textkomprimierungslevel
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// Definiert den PDF-Standard
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// Speichert die Präsentation als PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Das folgende Beispiel zeigt, wie PowerPoint mit versteckten Folien in PDF konvertiert wird. 
```cpp
// Instanziert eine Presentation-Klasse, die eine PowerPoint-Datei repräsentiert
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// Instanziert die PdfOptions-Klasse
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Fügt versteckte Folien hinzu
pdfOptions->set_ShowHiddenSlides(true);
// Speichert die Präsentation als PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Das folgende Beispiel zeigt, wie PowerPoint in ein passwortgeschütztes PDF konvertiert wird. 
```cpp
// Instanziert ein Presentation-Objekt, das eine PowerPoint-Datei darstellt
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// Setzt das PDF-Passwort und die Zugriffsrechte
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// Speichert die Präsentation als PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```
Das folgende Beispiel zeigt, wie PowerPoint mit Notizen in PDF konvertiert wird. 
```cpp
// Instanziert ein Presentation-Objekt, das eine Präsentationsdatei darstellt
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## Siehe auch

* Klasse [SaveOptions](../saveoptions/)
* Klasse [IPdfOptions](../ipdfoptions/)
* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)