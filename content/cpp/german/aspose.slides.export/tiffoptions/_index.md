---
title: TiffOptions
second_title: Aspose.Slides für C++ API Referenz
description: Stellt Optionen bereit, die steuern, wie eine Präsentation im TIFF-Format gespeichert wird.
type: docs
weight: 768
url: /de/aspose.slides.export/tiffoptions/
---
## TiffOptions Klasse


Provides options that control how a presentation is saved in TIFF format.

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | Gibt den Algorithmus zum Umwandeln eines Farbbildes in ein Schwarzweiß-Bild an. Diese Option wird nur angewendet, wenn [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) auf [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) oder [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) eingestellt ist. Lesen [BlackWhiteConversionMode](../blackwhiteconversionmode/). Standardwert ist [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | Gibt den Kompressionstyp an. Lesen [TiffCompressionTypes](../tiffcompressiontypes/). |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Gibt die Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Liest [System::String](../../system/string/). |
| **uint32_t** [get_DpiX](./get_dpix/)() override | Gibt die horizontale Auflösung in Punkten pro Zoll an. Lesen **uint32_t**. |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | Gibt die vertikale Auflösung in Punkten pro Zoll an. Lesen **uint32_t**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gibt den visuellen Stil des Farbverlaufs zurück. Liest [GradientStyle](../../aspose.slides/gradientstyle/). |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | Gibt die Größe eines erzeugten TIFF-Bildes an. Standardwert ist 0x0, was bedeutet, dass die Bildgrößen anhand der Foliengröße der Präsentation berechnet werden. Lesen [System::Drawing::Size](../../system.drawing/size/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | Bietet Optionen, die das Aussehen von [Ink](../../aspose.slides.ink/)-Objekten im exportierten Dokument steuern. Nur-Lese [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | Gibt das Pixel-Format für die erzeugten Bilder an. Lesen [ImagePixelFormat](../imagepixelformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stellt ein Callback-Objekt für das Speichern von Fortschritts-Updates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lesen **bool**. Der Standardwert ist **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Ermittelt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../islideslayoutoptions/) auf der Seite platziert werden. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Lesen [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrfunktion des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopier-Konstruktieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | Gibt den Algorithmus zum Umwandeln eines Farbbildes in ein Schwarzweiß-Bild an. Diese Option wird nur angewendet, wenn [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) auf [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) oder [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) eingestellt ist. Schreiben [BlackWhiteConversionMode](../blackwhiteconversionmode/). Standardwert ist [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/). |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | Gibt den Kompressionstyp an. Schreiben [TiffCompressionTypes](../tiffcompressiontypes/). |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Legt die Schriftart fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Schreiben [System::String](../../system/string/). |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | Gibt die horizontale Auflösung in Punkten pro Zoll an. Schreiben **uint32_t**. |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | Gibt die vertikale Auflösung in Punkten pro Zoll an. Schreiben **uint32_t**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Legt den visuellen Stil des Farbverlaufs fest. Schreiben [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | Gibt die Größe eines erzeugten TIFF-Bildes an. Standardwert ist 0x0, was bedeutet, dass die Bildgrößen anhand der Foliengröße der Präsentation berechnet werden. Schreiben [System::Drawing::Size](../../system.drawing/size/). |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | Gibt das Pixel-Format für die erzeugten Bilder an. Schreiben [ImagePixelFormat](../imagepixelformat/). |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stellt ein Callback-Objekt für das Speichern von Fortschritts-Updates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Gibt an, ob beim Speichern der Präsentation Hyperlinks mit JavaScript-Aufrufen übersprungen werden sollen. Schreiben **bool**. Der Standardwert ist **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../islideslayoutoptions/) auf der Seite platziert werden. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Gibt ein Objekt zurück oder setzt es, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreiben [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt geteilt). Erlaubt das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [TiffOptions](./tiffoptions/)() | Standard-Konstruktor. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in eine Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Hinweise


Das folgende Beispiel zeigt, wie man PowerPoint mit Standardgröße in TIFF konvertiert.
```cpp
// Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// Speichert die Präsentation als TIFF-Dokument
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
 Das folgende Beispiel zeigt, wie man PowerPoint mit benutzerdefinierter Größe in TIFF konvertiert.
```cpp
// Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// Instanziiere die TiffOptions-Klasse
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// Kompressionstyp festlegen
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// Kompressionstypen
// Default - Gibt das Standardkompressionsschema (LZW) an.
// None - Gibt an, dass keine Kompression verwendet wird.
// CCITT3
// CCITT4
// LZW
// RLE
// Die Farbtiefe hängt vom Kompressionstyp ab und kann nicht manuell festgelegt werden.
// Die Auflösungseinheit ist immer gleich "2" (Punkte pro Zoll)
// DPI des Bildes festlegen
opts->set_DpiX(200);
opts->set_DpiY(100);
// Bildgröße festlegen
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// Speichert die Präsentation als TIFF mit der angegebenen Bildgröße
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
 Das folgende Beispiel zeigt, wie man PowerPoint mit benutzerdefiniertem Bild-Pixel-Format in TIFF konvertiert.
```cpp
// Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// Speichert die Präsentation als TIFF mit der angegebenen Bildgröße
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## Siehe auch

* Klasse [SaveOptions](../saveoptions/)
* Klasse [ITiffOptions](../itiffoptions/)
* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)