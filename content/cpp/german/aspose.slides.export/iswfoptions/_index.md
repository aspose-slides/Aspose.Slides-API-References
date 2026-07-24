---
title: ISwfOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Bietet Optionen, die steuern, wie eine Präsentation im SWF-Format gespeichert wird.
type: docs
weight: 469
url: /de/aspose.slides.export/iswfoptions/
---
## ISwfOptions Klasse

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkomparativvergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkomparativvergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **bool** [get_Compressed](./get_compressed/)() | Legt fest, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Der Standardwert ist **true**. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | Gibt die Schriftart zurück, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Liest [System::String](../../system/string/). |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | Aktiviere/Deaktiviere das Kontextmenü. Standard ist true. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | Gibt den visuellen Stil des Farbverlaufs zurück. Liest [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | Legt die Qualität von JPEG-Bildern fest. \n\n Standard ist 95. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | Bild, das als Logo in der oberen rechten Ecke des Viewers angezeigt wird. \n\n Das Bild sollte ein PNG mit 32×64 Pixel sein, andernfalls kann das Logo fehlerhaft angezeigt werden. |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | Ermittelt die vollständige Hyperlink-Adresse für ein Logo. Wirksam nur, wenn ein [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) angegeben ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | Stellt ein Callback-Objekt für das Speichern von Fortschritts-Updates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | Anzeige/Verstecken des unteren Bereichs. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | Anzeige/Verstecken des Vollbild-Buttons. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist **false**. |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | Anzeige/Verstecken der linken Seite. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | Legt fest, ob ein Rand um die Seiten angezeigt werden soll. Standard ist true. |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | Anzeige/Verstecken des Seiten-Steppers. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | Anzeige/Verstecken des Suchbereichs. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | Anzeige/Verstecken des gesamten oberen Bereichs. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | Legt fest, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese **bool**. Der Standardwert ist **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | Ermittelt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../islideslayoutoptions/) auf der Seite platziert werden. Diese Eigenschaft unterstützt das Zuweisen von Objekten vom Typ **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** nicht. |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | Starten mit geöffneter linker Seite. Kann in flashvars überschrieben werden. Standard ist false. |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | Legt fest, ob das erzeugte SWF-Dokument den integrierten Dokumentviewer enthalten soll oder nicht. Standard ist **true**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Liest [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs ist. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das Sentinels-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referenz vergleicht Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den geteilten Referenzzähler um den angegebenen Wert. |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | Legt fest, ob das erzeugte SWF-Dokument komprimiert werden soll oder nicht. Der Standardwert ist **true**. |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Setzt die Schriftart, die verwendet wird, wenn die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | Aktiviere/Deaktiviere das Kontextmenü. Standard ist true. |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Setzt den visuellen Stil des Farbverlaufs. Schreibt [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | Legt die Qualität von JPEG-Bildern fest. \n\n Standard ist 95. |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Bild, das als Logo in der oberen rechten Ecke des Viewers angezeigt wird. \n\n Das Bild sollte ein PNG mit 32×64 Pixel sein, andernfalls kann das Logo fehlerhaft angezeigt werden. |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | Setzt die vollständige Hyperlink-Adresse für ein Logo. Wirksam nur, wenn ein [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) angegeben ist. |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Stellt ein Callback-Objekt für das Speichern von Fortschritts-Updates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | Anzeige/Verstecken des unteren Bereichs. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | Anzeige/Verstecken des Vollbild-Buttons. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Legt fest, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standard ist **false**. |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | Anzeige/Verstecken der linken Seite. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | Legt fest, ob ein Rand um die Seiten angezeigt werden soll. Standard ist true. |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | Anzeige/Verstecken des Seiten-Steppers. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | Anzeige/Verstecken des Suchbereichs. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | Anzeige/Verstecken des gesamten oberen Bereichs. Kann in flashvars überschrieben werden. Standard ist true. |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | Legt fest, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreibt **bool**. Der Standardwert ist **false**. |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | Setzt den Modus, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../islideslayoutoptions/) auf der Seite platziert werden. Diese Eigenschaft unterstützt das Zuweisen von Objekten vom Typ **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** nicht. |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | Starten mit geöffneter linker Seite. Kann in flashvars überschrieben werden. Standard ist false. |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | Legt fest, ob das erzeugte SWF-Dokument den integrierten Dokumentviewer enthalten soll oder nicht. Standard ist **true**. |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreibt [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Wechseln von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den geteilten Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den geteilten Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert die C#-Konstruktion typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das Sentinels-Objekt [LockContext](../../system/lockcontext/) verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [ISaveOptions](../isaveoptions/)
* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)