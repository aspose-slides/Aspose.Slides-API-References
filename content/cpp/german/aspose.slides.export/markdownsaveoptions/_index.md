---
title: MarkdownSaveOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Optionen dar, die steuern, wie die Präsentation als Markdown gespeichert wird.
type: docs
weight: 547
url: /de/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions Klasse

Stellt Optionen dar, die steuern, wie die Präsentation als Markdown gespeichert wird.

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | Gibt den Basis-Pfad an, in dem das Dokument mit Ressourcen gespeichert wird. Standard ist das aktuelle Verzeichnis der Anwendung. |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | Gibt die Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Liest [System::String](../../system/string/). |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | Gibt die Markdown-Spezifikation an, nach der die Präsentation konvertiert wird. Standard ist **TextOnly**. |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | Gibt die Markdown-Spezifikation an, nach der die Präsentation konvertiert wird. Standard ist **Multi-markdown**. |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | Gibt den visuellen Stil des Farbverlaufs zurück. Liest [GradientStyle](../../aspose.slides/gradientstyle/). |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Gibt an, wie wiederholte reguläre Leerzeichen beim Markdown-Export behandelt werden sollen. |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | Gibt den Ordnernamen zum Speichern von Bildern an. Standard ist **[Images](../../aspose.slides/images/)**. |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | Gibt an, ob das erzeugte Dokument Zeilenumbrüche \r (Macintosh), \n (Unix) oder \r\n (Windows) verwenden soll. Standard ist **Unix**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | Stellt ein Callback-Objekt für das Speichern von Fortschritts-Updates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | Wenn auf **true** gesetzt, werden leere oder nur aus Leerzeichen bestehende Zeilen aus dem finalen Markdown-Ausgabe entfernt. Standard ist **false**. |
| **bool** [get_ShowComments](./get_showcomments/)() const | Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll oder nicht. Standard ist **false**. |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht. Standard ist **false**. |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll oder nicht. Standard ist **false**. |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Lese **bool**. Der Standardwert ist **false**. |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Ermittelt die Formatzeichenfolge, die für Folienzahl-Überschriften in der Markdown-Ausgabe verwendet wird. Das Format muss den Platzhalter \"{0}\" enthalten, der beim Export durch den Folienindex ersetzt wird. Beispiel: \"# Slide {0}\" erzeugt \"# Slide 1\", \"# Slide 2\" usw. |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | Gibt ein Objekt zurück bzw. setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Liest [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/) Methode. Ermöglicht das Hashen von benutzerdefinierten Objekten. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/) Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C# 'is' Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock() Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächter-Objekt verwenden. |
| [MarkdownSaveOptions](./markdownsaveoptions/)() | Konstruktor. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzanzahl um den angegebenen Wert. |
| [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | Gibt den Basis-Pfad an, in dem das Dokument mit Ressourcen gespeichert wird. Standard ist das aktuelle Verzeichnis der Anwendung. |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | Setzt die Schriftart, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | Gibt die Markdown-Spezifikation an, nach der die Präsentation konvertiert wird. Standard ist **TextOnly**. |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | Gibt die Markdown-Spezifikation an, nach der die Präsentation konvertiert wird. Standard ist **Multi-markdown**. |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | Setzt den visuellen Stil des Farbverlaufs. Schreibe [GradientStyle](../../aspose.slides/gradientstyle/). |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Gibt an, wie wiederholte reguläre Leerzeichen beim Markdown-Export behandelt werden sollen. |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | Gibt den Ordnernamen zum Speichern von Bildern an. Standard ist **[Images](../../aspose.slides/images/)**. |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | Gibt an, ob das erzeugte Dokument Zeilenumbrüche \r (Macintosh), \n (Unix) oder \r\n (Windows) verwenden soll. Standard ist **Unix**. |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | Stellt ein Callback-Objekt für das Speichern von Fortschritts-Updates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | Wenn auf **true** gesetzt, werden leere oder nur aus Leerzeichen bestehende Zeilen aus dem finalen Markdown-Ausgabe entfernt. Standard ist **false**. |
| void [set_ShowComments](./set_showcomments/)(**bool**) | Gibt an, ob das erzeugte Dokument Kommentare anzeigen soll oder nicht. Standard ist **false**. |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | Gibt an, ob das erzeugte Dokument versteckte Folien einbeziehen soll oder nicht. Standard ist **false**. |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | Gibt an, ob das erzeugte Dokument die Nummer jeder Folie anzeigen soll oder nicht. Standard ist **false**. |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreibe **bool**. Der Standardwert ist **false**. |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Setzt die Formatzeichenfolge, die für Folienzahl-Überschriften in der Markdown-Ausgabe verwendet wird. Das Format muss den Platzhalter \"{0}\" enthalten, der beim Export durch den Folienindex ersetzt wird. Beispiel: \"# Slide {0}\" erzeugt \"# Slide 1\", \"# Slide 2\" usw. |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | Gibt ein Objekt zurück bzw. setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreibe [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern auf den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/) Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert die C# typeof([System.Object](../../system/object/)) Konstruktion. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock() Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/) Wächter-Objekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Wird für jedes nicht-SVG-Bild (Bitmap oder Metadatei) während des Markdown-Exports aufgerufen. Gibt **true** zurück, um den angegebenen *Link* zu verwenden, oder **false**, um die Standard-Speichermethode anzuwenden. |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Wird für jedes SVG-Bild während des Markdown-Exports aufgerufen. Gibt **true** zurück, um den angegebenen *Link* zu verwenden, oder **false**, um die Standard-Speichermethode anzuwenden. |

## Bemerkungen

Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## Siehe auch

* Klasse [SaveOptions](../saveoptions/)
* Namensraum [Aspose::Slides::Export](../)
* Bibliothek [Aspose.Slides](../../)