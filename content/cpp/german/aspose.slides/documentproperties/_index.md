---
title: DocumentProperties
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt Eigenschaften einer Präsentation dar.
type: docs
weight: 794
url: /de/aspose.slides/documentproperties/
---
## DocumentProperties Klasse


Stellt Eigenschaften einer Präsentation dar.

```cpp
class DocumentProperties : public Aspose::Slides::IDocumentProperties,
                           public Aspose::Slides::IGenericCloneable<System::SharedPtr<Aspose::Slides::IDocumentProperties>>
```

## Methoden

| Method | Description |
| --- | --- |
| void [ClearBuiltInProperties](./clearbuiltinproperties/)() override | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| void [ClearCustomProperties](./clearcustomproperties/)() override | Entfernt alle benutzerdefinierten Eigenschaften. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Clone](./clone/)() override | Klonen des aktuellen Objekts |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [CloneT](./clonet/)() override | Klonen des aktuellen Objekts |
| **bool** [ContainsCustomProperty](./containscustomproperty/)([System::String](../../system/string/)) override | Überprüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
|  [DocumentProperties](./documentproperties/)() | Initialisiert eine neue Instanz der Klasse [DocumentProperties](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte anhand der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-Stil von Fließkomma-Vergleichen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-Stil von Fließkomma-Vergleichen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_ApplicationTemplate](./get_applicationtemplate/)() override | Gibt die Vorlage einer Anwendung zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AppVersion](./get_appversion/)() override | Gibt die Anwendungsversion zurück. Nur lesend [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Author](./get_author/)() override | Gibt den Autor einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Category](./get_category/)() override | Gibt die Kategorie einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Comments](./get_comments/)() override | Gibt die Kommentare einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Company](./get_company/)() override | Gibt die Firmen-Eigenschaft zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentStatus](./get_contentstatus/)() override | Gibt den Inhaltsstatus einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_ContentType](./get_contenttype/)() override | Gibt den Inhaltstyp einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| **int32_t** [get_CountOfCustomProperties](./get_countofcustomproperties/)() override | Gibt die tatsächliche Anzahl benutzerdefinierter Eigenschaften in einer Sammlung zurück. Nur lesend **int32_t**. |
| [System::DateTime](../../system/datetime/) [get_CreatedTime](./get_createdtime/)() override | Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Lesen [System::DateTime](../../system/datetime/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHeadingPair](../iheadingpair/)\>\> [get_HeadingPairs](./get_headingpairs/)() override | Zeigt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an. Nur lesend [System::ArrayPtr<System::SharedPtr<IHeadingPair>>](../../system/arrayptr/). |
| **int32_t** [get_HiddenSlides](./get_hiddenslides/)() override | Gibt die Anzahl ausgeblendeter Folien in einem Präsentationsdokument zurück. Nur lesend **int32_t**. |
| [System::String](../../system/string/) [get_HyperlinkBase](./get_hyperlinkbase/)() override | Gibt die Dokument-Eigenschaft HyperlinkBase zurück. Lesen [System::String](../../system/string/). |
| **bool** [get_HyperlinksChanged](./get_hyperlinkschanged/)() override | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Lesen **bool**. |
| [System::String](../../system/string/) [get_Keywords](./get_keywords/)() override | Gibt die Schlüsselwörter einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastPrinted](./get_lastprinted/)() override | Gibt das Datum zurück, an dem eine Präsentation zuletzt ausgedruckt wurde. Lesen [System::DateTime](../../system/datetime/). |
| [System::String](../../system/string/) [get_LastSavedBy](./get_lastsavedby/)() override | Gibt den Namen der letzten Person zurück, die eine Präsentation geändert hat. Lesen [System::String](../../system/string/). |
| [System::DateTime](../../system/datetime/) [get_LastSavedTime](./get_lastsavedtime/)() override | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur lesend im Fall von [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (weil es intern während des [IPresentation](../ipresentation/)-Objektspeicherungsprozesses aktualisiert wird). Kann über die Instanz [DocumentProperties](./) geändert werden, die von Methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) zurückgegeben wird. Siehe das Beispiel in der Methodenzusammenfassung [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| **bool** [get_LinksUpToDate](./get_linksuptodate/)() override | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Lesen **bool**. |
| [System::String](../../system/string/) [get_Manager](./get_manager/)() override | Gibt die Manager-Eigenschaft zurück. Lesen [System::String](../../system/string/). |
| **int32_t** [get_MultimediaClips](./get_multimediaclips/)() override | Gibt die Gesamtzahl von Ton- oder Videoclips im Dokument zurück. Nur lesend **int32_t**. |
| [System::String](../../system/string/) [get_NameOfApplication](./get_nameofapplication/)() override | Gibt den Namen der Anwendung zurück. Lesen [System::String](../../system/string/). |
| **int32_t** [get_Notes](./get_notes/)() override | Gibt die Anzahl der Folien in einer Präsentation mit Notizen zurück. Nur lesend **int32_t**. |
| **int32_t** [get_Paragraphs](./get_paragraphs/)() override | Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, falls zutreffend. Nur lesend **int32_t**. |
| [System::String](../../system/string/) [get_PresentationFormat](./get_presentationformat/)() override | Gibt das beabsichtigte Format einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| **int32_t** [get_RevisionNumber](./get_revisionnumber/)() override | Gibt die Revisionsnummer der Präsentation zurück. Lesen **int32_t**. |
| **bool** [get_ScaleCrop](./get_scalecrop/)() override | Gibt den Anzeigemodus der Dokument-Vorschaubildes an. Setzen Sie dieses Element auf **true**, um das Skalieren des Vorschaubildes an die Anzeige zu ermöglichen. Setzen Sie dieses Element auf **false**, um das Beschneiden des Vorschaubildes zu ermöglichen, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Lesen **bool**. |
| **bool** [get_SharedDoc](./get_shareddoc/)() override | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Lesen **bool**. |
| **int32_t** [get_Slides](./get_slides/)() override | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück. Nur lesend **int32_t**. |
| [System::String](../../system/string/) [get_Subject](./get_subject/)() override | Gibt den Betreff einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | Gibt den Titel einer Präsentation zurück. Lesen [System::String](../../system/string/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_TitlesOfParts](./get_titlesofparts/)() override | Gibt den Titel jedes Dokumentteils an. Diese Teile sind keine Dokumentteile, sondern konzeptionelle Darstellungen von Dokumentabschnitten. Nur lesend [System::ArrayPtr<System::String>](../../system/arrayptr/). |
| [System::TimeSpan](../../system/timespan/) [get_TotalEditingTime](./get_totaleditingtime/)() override | Gesamte Bearbeitungszeit einer Präsentation. Lesen [System::TimeSpan](../../system/timespan/). |
| **int32_t** [get_Words](./get_words/)() override | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter zurück. Nur lesend **int32_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| [System::String](../../system/string/) [GetCustomPropertyName](./getcustompropertyname/)(**int32_t**) override | Gibt den Namen einer benutzerdefinierten Eigenschaft am angegebenen Index zurück. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **bool**\&) override | Erhält einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **int32_t**\&) override | Erhält einen benannten Ganzzahlwert aus den benutzerdefinierten Eigenschaften. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)\&) override | Erhält einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)\&) override | Erhält einen benannten Zeichenfolgenwert aus den benutzerdefinierten Eigenschaften. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **float**\&) override | Erhält einen benannten Float-Wert aus den benutzerdefinierten Eigenschaften. |
| void [GetCustomPropertyValue](./getcustompropertyvalue/)([System::String](../../system/string/), **double**\&) override | Erhält einen benannten Double-Wert aus den benutzerdefinierten Eigenschaften. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashing benutzerdefinierter Objekte. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabel](../isensitivitylabel/)\>\> [GetSensitivityLabels](./getsensitivitylabels/)() override | Erhält ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteigenschaften (Microsoft Information Protection SDK Metadata). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [idx_get](./idx_get/)([System::String](../../system/string/)) override | Gibt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft zurück. Lesen [System::Object](../../system/object/). |
| void [idx_set](./idx_set/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Setzt die mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft. Schreiben [System::Object](../../system/object/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement für das Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erzeugt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopie-Konstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| **bool** [RemoveCustomProperty](./removecustomproperty/)([System::String](../../system/string/)) override | Entfernt eine mit einem angegebenen Namen verknüpfte benutzerdefinierte Eigenschaft. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| void [set_ApplicationTemplate](./set_applicationtemplate/)([System::String](../../system/string/)) override | Setzt die Vorlage einer Anwendung. Schreiben [System::String](../../system/string/). |
| void [set_Author](./set_author/)([System::String](../../system/string/)) override | Setzt den Autor einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_Category](./set_category/)([System::String](../../system/string/)) override | Setzt die Kategorie einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_Comments](./set_comments/)([System::String](../../system/string/)) override | Setzt die Kommentare einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_Company](./set_company/)([System::String](../../system/string/)) override | Setzt die Firmen-Eigenschaft. Schreiben [System::String](../../system/string/). |
| void [set_ContentStatus](./set_contentstatus/)([System::String](../../system/string/)) override | Setzt den Inhaltsstatus einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_ContentType](./set_contenttype/)([System::String](../../system/string/)) override | Setzt den Inhaltstyp einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_CreatedTime](./set_createdtime/)([System::DateTime](../../system/datetime/)) override | Gibt das Erstellungsdatum einer Präsentation zurück. Werte sind in UTC. Schreiben [System::DateTime](../../system/datetime/). |
| void [set_HyperlinkBase](./set_hyperlinkbase/)([System::String](../../system/string/)) override | Setzt die Dokument-Eigenschaft HyperlinkBase. Schreiben [System::String](../../system/string/). |
| void [set_HyperlinksChanged](./set_hyperlinkschanged/)(**bool**) override | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller aktualisiert wurden. Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren. Schreiben **bool**. |
| void [set_Keywords](./set_keywords/)([System::String](../../system/string/)) override | Setzt die Schlüsselwörter einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_LastPrinted](./set_lastprinted/)([System::DateTime](../../system/datetime/)) override | Gibt das Datum zurück, an dem eine Präsentation zuletzt ausgedruckt wurde. Schreiben [System::DateTime](../../system/datetime/). |
| void [set_LastSavedBy](./set_lastsavedby/)([System::String](../../system/string/)) override | Setzt den Namen der letzten Person, die eine Präsentation geändert hat. Schreiben [System::String](../../system/string/). |
| void [set_LastSavedTime](./set_lastsavedtime/)([System::DateTime](../../system/datetime/)) override | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde. Werte sind in UTC. Nur lesend im Fall von [Presentation::get_DocumentProperties](../presentation/get_documentproperties/) (weil es intern während des [IPresentation](../ipresentation/)-Objektspeicherungsprozesses aktualisiert wird). Kann über die Instanz [DocumentProperties](./) geändert werden, die von Methode [IPresentationInfo::ReadDocumentProperties](../ipresentationinfo/readdocumentproperties/) zurückgegeben wird. Siehe das Beispiel in der Methodenzusammenfassung [IPresentationInfo::UpdateDocumentProperties](../ipresentationinfo/updatedocumentproperties/). |
| void [set_LinksUpToDate](./set_linksuptodate/)(**bool**) override | Gibt an, ob Hyperlinks in einem Dokument aktuell sind. Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind. Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind. Schreiben **bool**. |
| void [set_Manager](./set_manager/)([System::String](../../system/string/)) override | Setzt die Manager-Eigenschaft. Schreiben [System::String](../../system/string/). |
| void [set_NameOfApplication](./set_nameofapplication/)([System::String](../../system/string/)) override | Setzt den Namen der Anwendung. Schreiben [System::String](../../system/string/). |
| void [set_PresentationFormat](./set_presentationformat/)([System::String](../../system/string/)) override | Setzt das beabsichtigte Format einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_RevisionNumber](./set_revisionnumber/)(**int32_t**) override | Setzt die Revisionsnummer der Präsentation. Schreiben **int32_t**. |
| void [set_ScaleCrop](./set_scalecrop/)(**bool**) override | Gibt den Anzeigemodus der Dokument-Vorschaubildes an. Setzen Sie dieses Element auf **true**, um das Skalieren des Vorschaubildes an die Anzeige zu ermöglichen. Setzen Sie dieses Element auf **false**, um das Beschneiden des Vorschaubildes zu ermöglichen, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen. Schreiben **bool**. |
| void [set_SharedDoc](./set_shareddoc/)(**bool**) override | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird. Schreiben **bool**. |
| void [set_Subject](./set_subject/)([System::String](../../system/string/)) override | Setzt den Betreff einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | Setzt den Titel einer Präsentation. Schreiben [System::String](../../system/string/). |
| void [set_TotalEditingTime](./set_totaleditingtime/)([System::TimeSpan](../../system/timespan/)) override | Gesamte Bearbeitungszeit einer Präsentation. Schreiben [System::TimeSpan](../../system/timespan/). |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **bool**) override | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **int32_t**) override | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::DateTime](../../system/datetime/)) override | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), [System::String](../../system/string/)) override | Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **float**) override | Setzt eine benannte Float-benutzerdefinierte Eigenschaft. |
| void [SetCustomPropertyValue](./setcustompropertyvalue/)([System::String](../../system/string/), **double**) override | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzahl. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzahl zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenfolgen. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement für das Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzahl. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzahl. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Hinweise


Das folgende Beispiel zeigt, wie man integrierte Eigenschaften von PowerPoint [Presentation](../presentation/) zugreift.

```cpp
// Instanziieren Sie die Presentation-Klasse, die die Präsentation darstellt
auto pres = System::MakeObject<Presentation>(dataDir + u"AccessBuiltin Properties.pptx");

// Create a reference to IDocumentProperties object associated with Presentation
System::SharedPtr<IDocumentProperties> documentProperties = pres->get_DocumentProperties();
// Display the builtin properties
System::Console::WriteLine(System::String(u"Category : ") + documentProperties->get_Category());
System::Console::WriteLine(System::String(u"Current Status : ") + documentProperties->get_ContentStatus());
System::Console::WriteLine(System::String(u"Creation Date : ") + documentProperties->get_CreatedTime());
System::Console::WriteLine(System::String(u"Author : ") + documentProperties->get_Author());
System::Console::WriteLine(System::String(u"Description : ") + documentProperties->get_Comments());
```
Das folgende Beispiel zeigt, wie man integrierte Eigenschaften von PowerPoint [Presentation](../presentation/) verändert.

```cpp
// Instanziieren Sie die Presentation-Klasse, die die Präsentation darstellt
auto presentation = System::MakeObject<Presentation>(dataDir + u"ModifyBuiltinProperties.pptx");

// Erstellen Sie eine Referenz zum IDocumentProperties-Objekt, das mit der Presentation verknüpft ist
System::SharedPtr<IDocumentProperties> documentProperties = presentation->get_DocumentProperties();
// Setzen Sie die integrierten Eigenschaften
documentProperties->set_Author(u"Aspose.Slides for .NET");
documentProperties->set_Title(u"Modifying Presentation Properties");
documentProperties->set_Subject(u"Aspose Subject");
// Speichern Sie Ihre Präsentation in einer Datei
presentation->Save(u"DocumentProperties_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Klasse [IDocumentProperties](../idocumentproperties/)
* Klasse [IGenericCloneable](../igenericcloneable/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)