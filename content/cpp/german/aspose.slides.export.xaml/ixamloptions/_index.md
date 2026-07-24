---
title: IXamlOptions
second_title: Aspose.Slides für C++ API-Referenz
description: Optionen, die steuern, wie ein XAML-Dokument gespeichert wird.
type: docs
weight: 1
url: /de/aspose.slides.export.xaml/ixamloptions/
---
## IXamlOptions Klasse

Optionen, die steuern, wie ein XAML-Dokument gespeichert wird.

```cpp
class IXamlOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../../aspose.slides.export/isaveoptions/get_defaultregularfont/)() | Gibt die Schriftart zurück, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Liest [System::String](../../system/string/). |
| virtual **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() | Bestimmt, ob verborgene Folien exportiert werden. |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../../aspose.slides.export/isaveoptions/get_gradientstyle/)() | Gibt den visuellen Stil des Farbverlaufs zurück. Liest [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\> [get_OutputSaver](./get_outputsaver/)() | Stellt eine Implementierung des IOutputSaver-Interfaces dar. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../../aspose.slides.export/isaveoptions/get_progresscallback/)() | Stellt ein Rückruffunktionsobjekt für das Speichern von Fortschrittsupdates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual **bool** [get_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/get_skipjavascriptlinks/)() | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Liest **bool**. Der Standardwert ist **false**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../../aspose.slides.export/isaveoptions/get_warningcallback/)() | Gibt ein Objekt zurück, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Liest [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C#-Anweisung lock(). Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von String und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_DefaultRegularFont](../../aspose.slides.export/isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | Setzt die Schriftart, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../system/string/). |
| virtual void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) | Bestimmt, ob verborgene Folien exportiert werden. |
| virtual void [set_GradientStyle](../../aspose.slides.export/isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | Setzt den visuellen Stil des Farbverlaufs. Schreibt [GradientStyle](../../aspose.slides/gradientstyle/). |
| virtual void [set_OutputSaver](./set_outputsaver/)([System::SharedPtr](../../system/sharedptr/)\<[IXamlOutputSaver](../ixamloutputsaver/)\>) | Stellt eine Implementierung des IOutputSaver-Interfaces dar. |
| virtual void [set_ProgressCallback](../../aspose.slides.export/isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | Stellt ein Rückruffunktionsobjekt für das Speichern von Fortschrittsupdates in Prozent dar. Siehe [IProgressCallback](../../aspose.slides/iprogresscallback/). |
| virtual void [set_SkipJavaScriptLinks](../../aspose.slides.export/isaveoptions/set_skipjavascriptlinks/)(**bool**) | Gibt an, ob Hyperlinks mit JavaScript-Aufrufen beim Speichern der Präsentation übersprungen werden sollen. Schreibt **bool**. Der Standardwert ist **false**. |
| virtual void [set_WarningCallback](../../aspose.slides.export/isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | Setzt ein Objekt, das Warnungen empfängt und entscheidet, ob der Ladevorgang fortgesetzt oder abgebrochen wird. Schreibt [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C#-Anweisung lock(). Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen intelligente Zeiger oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Bemerkungen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Siehe auch

* Klasse [ISaveOptions](../../aspose.slides.export/isaveoptions/)
* Namensraum [Aspose::Slides::Export::Xaml](../)
* Bibliothek [Aspose.Slides](../../)