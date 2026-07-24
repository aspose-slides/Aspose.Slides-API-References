---
title: SwfOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.
type: docs
weight: 742
url: /de/aspose.slides.export/swfoptions/
---
## SwfOptions Klasse


Bietet Optionen, die steuern, wie eine Präsentation im Swf-Format gespeichert wird.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## Methoden

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **bool** [get_Compressed](./get_compressed/)() override | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standardwert ist **true**. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Gibt die Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Liest [System::String](../../system/string/). |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | Aktiviert/deaktiviert das Kontextmenü. Standardwert ist true. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gibt den visuellen Stil des Farbverlaufs zurück. Liest [GradientStyle](../../aspose.slides/gradientstyle/). |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | Legt die Qualität der JPEG-Bilder fest. Standardwert ist 95. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | Bild, das als Logo in der oberen rechten Ecke des Viewers angezeigt wird. Das Bild sollte ein 32x64 Pixel großes PNG sein, sonst kann das Logo fehlerhaft dargestellt werden. |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | Liefert die vollständige Hyperlink-Adresse für ein Logo. Wirkt nur, wenn ein [set_LogoImageBytes()](./set_logoimagebytes/) angegeben ist. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | Zeigt/verbirgt das untere Feld. Kann in flashvars überschrieben werden. Standardwert ist true. |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | Zeigt/verbirgt die Vollbild-Schaltfläche. Kann in flashvars überschrieben werden. Standardwert ist true. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist **false**. |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | Zeigt/verbirgt das linke Feld. Kann in flashvars überschrieben werden. Standardwert ist true. |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | Gibt an, ob ein Rand um die Seiten angezeigt werden soll. Standardwert ist true. |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | Zeigt/verbirgt die Seitennavigation. Kann in flashvars überschrieben werden. Standardwert ist true. |
| **bool** [get_ShowSearch](./get_showsearch/)() override | Zeigt/verbirgt den Suchbereich. Kann in flashvars überschrieben werden. Standardwert ist true. |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | Zeigt/verbirgt das gesamte obere Feld. Kann in flashvars überschrieben werden. Standardwert ist true. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Liest **bool**. Der Standardwert ist **false**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | Liefert den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation [ISlidesLayoutOptions](../islideslayoutoptions/) exportiert wird. Diese Eigenschaft unterstützt das Zuweisen von Objekten des Typs [HandoutLayoutingOptions](../handoutlayoutingoptions/) nicht. |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | Startet mit geöffnetem linkem Feld. Kann in flashvars überschrieben werden. Standardwert ist false. |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentenviewer enthalten soll oder nicht. Standardwert ist **true**. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Gibt ein Objekt zurück bzw. setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Liest [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Liefert den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | Gibt an, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Standardwert ist **true**. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Legt die Schriftart fest, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | Aktiviert/deaktiviert das Kontextmenü. Standardwert ist true. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Setzt den visuellen Stil des Farbverlaufs. Schreibt [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | Legt die Qualität der JPEG-Bilder fest. Standardwert ist 95. |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Bild, das als Logo in der oberen rechten Ecke des Viewers angezeigt wird. Das Bild sollte ein 32x64 Pixel großes PNG sein, sonst kann das Logo fehlerhaft dargestellt werden. |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | Setzt die vollständige Hyperlink-Adresse für ein Logo. Wirkt nur, wenn ein [set_LogoImageBytes()](./set_logoimagebytes/) angegeben ist. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stellt ein Callback-Objekt für das Speichern von Fortschrittsaktualisierungen in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | Zeigt/verbirgt das untere Feld. Kann in flashvars überschrieben werden. Standardwert ist true. |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | Zeigt/verbirgt die Vollbild-Schaltfläche. Kann in flashvars überschrieben werden. Standardwert ist true. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist **false**. |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | Zeigt/verbirgt das linke Feld. Kann in flashvars überschrieben werden. Standardwert ist true. |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | Gibt an, ob ein Rand um die Seiten angezeigt werden soll. Standardwert ist true. |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | Zeigt/verbirgt die Seitennavigation. Kann in flashvars überschrieben werden. Standardwert ist true. |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | Zeigt/verbirgt den Suchbereich. Kann in flashvars überschrieben werden. Standardwert ist true. |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | Zeigt/verbirgt das gesamte obere Feld. Kann in flashvars überschrieben werden. Standardwert ist true. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreibe **bool**. Der Standardwert ist **false**. |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | Setzt den Modus, in dem Folien auf der Seite platziert werden, wenn eine Präsentation [ISlidesLayoutOptions](../islideslayoutoptions/) exportiert wird. Diese Eigenschaft unterstützt das Zuweisen von Objekten des Typs [HandoutLayoutingOptions](../handoutlayoutingoptions/) nicht. |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | Startet mit geöffnetem linkem Feld. Kann in flashvars überschrieben werden. Standardwert ist false. |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | Gibt an, ob das erzeugte SWF-Dokument den integrierten Dokumentenviewer enthalten soll oder nicht. Standardwert ist **true**. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Gibt ein Objekt zurück bzw. setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreibe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n'th Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Liefert den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den geteilten Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
|  [SwfOptions](./swfoptions/)() |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Hinweise


Das folgende Beispiel zeigt, wie man PowerPoint in SWF Flash konvertiert. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## Siehe auch

* Klasse [SaveOptions](../saveoptions/)
* Klasse [ISwfOptions](../iswfoptions/)
* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)