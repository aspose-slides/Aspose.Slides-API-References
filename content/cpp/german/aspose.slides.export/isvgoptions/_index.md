---
title: ISVGOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine SVG-Option dar.
type: docs
weight: 404
url: /de/aspose.slides.export/isvgoptions/
---
## ISVGOptions Klasse


Stellt eine SVG-Option dar.

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert gleich ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert gleich ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Gibt die Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Liest [System::String](../../system/string/). |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Ist es true, werden die beschnittenen Teile entfernt, ist es false, werden sie im Dokument serialisiert (was möglicherweise zu einer größeren Datei führt). Liest **bool**. |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Liest **bool**. |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | Erhält einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf **true** gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt. |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Gradienten. Liest **bool**. |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 kann keine Einrückungen für Marker definieren. [Aspose.Slides](../../aspose.slides/) SVG-Schreibengine hat eine Lösung für dieses Problem: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet ein solches Verhalten ab. Liest **bool**. |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | Bestimmt eine Methode zum Umgang mit extern geladenen Schriften. Liest [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Gibt den visuellen Stil des Gradienten zurück. Liest [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | Stellt Optionen bereit, die das Erscheinungsbild von [Ink](../../aspose.slides.ink/)-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Bestimmt die JPEG-Codierungsqualität. Liest **int32_t**. |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | Gibt die untere Auflösungsgrenze für Metadatei-Rasterung zurück. Liest **int32_t**. |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | Stellt das Komprimierungsniveau der Bilder dar. Liest [PicturesCompression](../picturescompression/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Liest [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Liest **bool**. Der Standardwert ist **false**. |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | Bestimmt, ob beim Rendern die angegebene Drehung der Form ausgeführt werden soll oder nicht. Liest **bool**. Standardwert ist true. |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht. Liest **bool**. Standardwert ist false. |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Liest **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Liest [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# `is`-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstelle ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzanzahl um den angegebenen Wert. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Setzt die Schriftart, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Ist es true, werden die beschnittenen Teile entfernt, ist es false, werden sie im Dokument serialisiert (was möglicherweise zu einer größeren Datei führt). Schreibe **bool**. |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | Bestimmt, ob der 3D-Text in SVG deaktiviert ist. Schreibe **bool**. |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | Setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn auf **true** gesetzt, werden Ligaturen in der gerenderten Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf **false** gesetzt. |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | Deaktiviert das Aufteilen von FromCornerX- und FromCenter-Gradienten. Schreibe **bool**. |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 kann keine Einrückungen für Marker definieren. [Aspose.Slides](../../aspose.slides/) SVG-Schreibengine hat eine Lösung für dieses Problem: Sie schneidet das Linienende mit Pfeil ab, sodass die Linie die Marker nicht überlappt. Diese Option schaltet ein solches Verhalten ab. Schreibe **bool**. |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | Bestimmt eine Methode zum Umgang mit extern geladenen Schriften. Schreibe [SvgExternalFontsHandling](../svgexternalfontshandling/). |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Setzt den visuellen Stil des Gradienten. Schreibe [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Bestimmt die JPEG-Codierungsqualität. Schreibe **int32_t**. |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | Setzt die untere Auflösungsgrenze für Metadatei-Rasterung. Schreibe **int32_t**. |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | Stellt das Komprimierungsniveau der Bilder dar. Schreibe [PicturesCompression](../picturescompression/). |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | Gibt eine Callback-Schnittstelle zurück und setzt sie, die es dem Benutzer ermöglicht, die Formkonvertierung zu steuern. Schreibe [ISvgShapeFormattingController](../isvgshapeformattingcontroller/). |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Schreibe **bool**. Der Standardwert ist **false**. |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | Bestimmt, ob beim Rendern die angegebene Drehung der Form ausgeführt werden soll oder nicht. Schreibe **bool**. Standardwert ist true. |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | Bestimmt, ob der Textrahmen in einen Renderbereich einbezogen wird oder nicht. Schreibe **bool**. Standardwert ist false. |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | Bestimmt, ob der Text auf einer Folie als Grafik gespeichert wird. Schreibe **bool**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreibe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte zu string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ISaveOptions](../isaveoptions/)
* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)