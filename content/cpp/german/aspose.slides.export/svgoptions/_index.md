---
title: SVGOptions
second_title: Aspose.Slides für C++ API Referenz
description: Stellt SVG-Optionen dar.
type: docs
weight: 703
url: /de/aspose.slides.export/svgoptions/
---
## SVGOptions Klasse

Stellt SVG-Optionen dar.

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Fließkommazahlen, bei dem zwei NaNs als gleich angesehen werden, obwohl NaN laut IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | Gibt Standard-Einstellungen zurück. Nur lesbar [SVGOptions](./). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Gibt die Schrift zurück, die verwendet wird, falls die Quellschrift nicht gefunden wird. Liest [System::String](../../system/string/). |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn wahr, werden die zugeschnittenen Teile entfernt, wenn falsch, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann). |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Lies **bool**. |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | Ermittelt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wird er auf **true** gesetzt, werden Ligaturen im gerenderten Ergebnis deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt. |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Lies **bool**. |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 kann keine Einrückungen für Marker definieren. [Aspose.Slides](../../aspose.slides/) SVG-Schreibengine hat dafür eine Umgehungslösung: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Lies **bool**. |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | Bestimmt, wie extern geladene Schriften verarbeitet werden. Lies [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gibt den visuellen Stil des Farbverlaufs zurück. Lies [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Stellt Optionen bereit, die das Aussehen von [Ink](../../aspose.slides.ink/)-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Bestimmt die JPEG-Kodierungsqualität. Lies **int32_t**. |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | Gibt die untere Auflösungsgrenze für die Rasterung von Metadateien zurück. Lies **int32_t**. |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | Stellt das Kompressionslevel für Bilder dar |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stellt ein Callback-Objekt zur Speicherung von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Lies [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | Gibt Einstellungen für die einfachste und kleinste SVG-Dateierzeugung zurück. Nur lesbar [SVGOptions](./). |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lies **bool**. Der Standardwert ist **false**. |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt werden soll. Lies **bool**. Der Standardwert ist wahr. |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | Bestimmt, ob das Textfeld in einen Renderbereich einbezogen wird. Lies **bool**. Der Standardwert ist falsch. |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Lies **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lies [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | Gibt Einstellungen für die genaueste SVG-Dateierzeugung zurück. Nur lesbar [SVGOptions](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Setzt die Schrift, die verwendet wird, falls die Quellschrift nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn wahr, werden die zugeschnittenen Teile entfernt, wenn falsch, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann). |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Schreibe **bool**. |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | Setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wird er auf **true** gesetzt, werden Ligaturen im gerenderten Ergebnis deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt. |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Verläufen. Schreibe **bool**. |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 kann keine Einrückungen für Marker definieren. [Aspose.Slides](../../aspose.slides/) SVG-Schreibengine hat dafür eine Umgehungslösung: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet dieses Verhalten aus. Schreibe **bool**. |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | Bestimmt, wie extern geladene Schriften verarbeitet werden. Schreibe [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Setzt den visuellen Stil des Farbverlaufs. Schreibe [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Bestimmt die JPEG-Kodierungsqualität. Schreibe **int32_t**. |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | Setzt die untere Auflösungsgrenze für die Rasterung von Metadateien. Schreibe **int32_t**. |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | Stellt das Kompressionslevel für Bilder dar |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stellt ein Callback-Objekt zur Speicherung von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Schreibe [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreibe **bool**. Der Standardwert ist **false**. |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | Bestimmt, ob die angegebene Drehung der Form beim Rendern ausgeführt werden soll. Schreibe **bool**. Der Standardwert ist wahr. |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | Bestimmt, ob das Textfeld in einen Renderbereich einbezogen wird. Schreibe **bool**. Der Standardwert ist falsch. |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Schreibe **bool**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreibe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [SVGOptions](./svgoptions/)() | Initialisiert eine neue Instanz der Klasse [SVGOptions](./). |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | Initialisiert eine neue Instanz der Klasse [SVGOptions](./) und gibt das Link-Embedding-Controller-Objekt an. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die Weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [SaveOptions](../saveoptions/)
* Klasse [ISVGOptions](../isvgoptions/)
* Namespace [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)